---
title: 「Ram,this is Steve.」一位接到Steve Jobs來電的軟體開發者的故事。
date: 2010-11-12T08:40:00+00:00
author: kouko
layout: post
categories:
  - Apple Rumors
  - Article
  - History
  - Steve Jobs
---

以下是iPad軟體「[Economy for iPad](http://itunes.apple.com/us/app/economy-for-ipad/id396544244?mt=8)」開發者Cascade Ram的blog上所刊載的「[A zombie keyboard, an app-store rejection, a call from Steve Jobs and the Economy-for-iPad app](http://blog.cascadesoft.net/2010/10/31/a-zombie-keyboard-an-app-store-rejection-a-call-from-steve-jobs-and-the-economy-for-ipad-app/) 」一文的翻譯，算是一個有趣（？）的小故事。按照慣例，由於翻譯水準問題，有心人士請直接看原文：

***

### 殭屍鍵盤、App Store審查退回、從Steve Jobs來的電話與Economy for iPad。

#### ﻿殭屍鍵盤（﻿﻿﻿﻿﻿The Zombie keyboard）

開發Economy for iPad這個軟體很有趣，同時有一部分也非常有挑戰性。其中之一是有關惱人的殭屍鍵盤問題。這個問題導致在相關的文字檢視元件解除鎖定後，軟體鍵盤仍然顯示在螢幕上。因此使用者將會看到一個殭屍鍵盤，但是沒有任何與其相關的文字物件。

#### 使用非官方API來解決殭屍鍵盤

在3:30am，我終於明白殭屍鍵盤的問題不是在我的代碼，而是在iPad SDK本身的問題。在當時，其實我因該收工了，不過並沒有。我進一步研究了問題，並發現使用非官方API（dismissKeyboard）可以完美的把鍵盤移除。在軟體意外控制與檢查respondsToSelector後，代碼似乎在合理範圍內很安全。（雖然我同意Apple禁止使用非官方API的理由。）

#### App Store審查退回

在九天的審查週期過後，我得到了一份措詞非常禮貌的回信，信中表示由於使用非官方API，軟體的申請已經被拒絕。由於這個非官方API是被用來解決官方API的問題，這看似是個Apple可能會破例的好機會。所以我向Apple的軟體審查委員會提出上訴。


#### 僵局

Apple的審查團隊的工作的非常好，他們持續與我聯繫（email與電話）並討論此事的細節。不過，我無法得知審查委員會給出確切答覆的時間。申訴似乎帶來了一個難題。一方面，非官方API的使用是由於SDK本身的錯誤，但是另一方面，允許非官方API將留下不好的先例。在此同時，軟體發佈的機會似乎沒有任何進展。在此時，我決定寫信給Steve Jobs。

#### 「Ram,this is Steve.」

將信件寄出的幾個小時後，當我在一個吵鬧的兒童足球場時，電話響了。來電者說「Ram，我是Steve。（Ram, this is Steve）」，由於這是由Apple發出的來電，因此這可能真的是Steve Jobs。當我詢問後，他證實了這點。

#### Steve Jobs的決定

﻿Steve Jobs與我討論我的上訴與「禁止非官方API」的政策。接著我問到由於SDK本身的錯誤導致非官方API的必要，是否可以破例。Steve Jobs重申了他的觀點，而我也接受了。我告訴他我會使用alternative UI來取代modal form sheet。移除form sheet （以及其缺陷）後，將不再需要使用非官方API。

#### 認真的人

Steve Jobs在創造高品質產品，以及他對用使用者體驗的熱情有著當之無愧的聲譽。我也發現他是一個注重執行細節與密切親自參與公司運作的人。（在這方面，很少有其他CEO是如此）。

與他透過電話交談又更進一步地印證了這點，同時也證明他也是個非常認真、在乎他人的人。事實上，他花了時間閱讀我的信件，思考軟體後並親自打電話給我，這是非常驚人的。

#### 結局

我在移除非官方API後，重新提交了「[Economy for iPad](http://itunes.apple.com/us/app/economy-for-ipad/id396544244?mt=8)」。這個軟體使用聯邦政府的資料來給使用者一個美國經濟的速寫。軟體審查委員會與審查小組慷慨地加快了軟體審查流程，現在軟體已經可以在App Store上下載了。我們從2008年（App Store開始營運的那年）就開始發佈iOS軟體，在我們所有的軟體中，這是有著最有趣的審查過程的一個軟體。我現在期待著這個軟體在iPad App Store中的表現。

via [A zombie keyboard, an app-store rejection, a call from Steve Jobs and the Economy-for-iPad app](http://blog.cascadesoft.net/2010/10/31/a-zombie-keyboard-an-app-store-rejection-a-call-from-steve-jobs-and-the-economy-for-ipad-app/)

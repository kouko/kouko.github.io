---
id: 14709
title: iCloud帳號入侵事件 —— Amazon認為不重要，可以直接顯示在網路上的那四碼，正是Apple認為夠安全，足以驗證身份的那四碼。
date: 2012-08-08T04:02:41+00:00
author: kouko
excerpt: 最近與Apple相關的資安問題中，最熱門的就是Wired編輯Mat Honan的iCloud帳號（=Apple ID）被入侵的事件了。
layout: post
categories:
  - Apple
  - Article
  - Bug
  - iCloud
---
<img title="iCloud-hack.jpg" src="/img/2012-08-08-apple-amazon-mat-honan-hacking/iCloud-hack.jpg" alt="iCloud hack" />

最近與Apple相關的資安問題中，最熱門的就是Wired編輯Mat Honan的iCloud帳號（=Apple ID）被入侵的事件了。

<img style="float: right; margin: 0 0 20px 20px;" title="matHonan_v4edit.jpg" src="/img/2012-08-08-apple-amazon-mat-honan-hacking/matHonan_v4edit.jpg" alt="MatHonan v4edit" width="250" border="0" />在短短的一個小時之內，他的Google帳號被駭客接手並且刪除、Twitter帳號也被盜走，並用來散發亂七八糟的訊息。最糟糕的，是他的Apple ID也被盜走，而駭客也利用Apple ID將他的iPhone、iPad與MacBook上的資料全部從遠端清除的一乾二淨。 

究竟駭客是如何盜走Honan的iCloud帳號？首先，根據Apple技術支援服務（AppleCare）的說法，要獲得某個人的iCloud存取權，只需要以下這些資訊：

  * Apple ID下登錄的信用卡號碼末四碼。
  * Apple ID的帳單地址。

只要有這些訊息，Apple的技術支援服務電話就會發出臨時密碼，此臨時密碼可以讓使用者獲得iCloud帳號完整的存取權限。

不過對於這次Mat Honan的案例，Apple發言人Natalie Kerris表示：

> “Apple takes customer privacy seriously and requires multiple forms of verification before resetting an Apple ID password. In this particular case, the customer’s data was compromised by a person who had acquired personal information about the customer. In addition, we found that our own internal policies were not followed completely. We are reviewing all of our processes for resetting account passwords to ensure our customers’ data is protected.”
>
> Apple非常認真地看待顧客的隱私，並且在重置Apple ID密碼之前，會要求各種形式的身份認證。在這個特別的案例下，顧客的資料被其他持有顧客個人情報的人所盜取。此外，我們也發現我們的內部政策並沒有被完全遵守。我們正在檢視我們重置密碼的所有流程，以確保我們顧客的資料受到保護。

不過最重要的是，駭客是如何取得Mat Honan的帳單地址，以及關鍵的信用卡末四碼？根據Mat Honan在Wired上所刊登的文章，以下是整個駭客過程⋯⋯

> 在被駭客的當晚，我試著釐清我的數位生活是如何被毀滅的。我的Google帳號被毀滅、Twitter帳號被凍結、我的手機由於被重置而一整個無用、而我一整個處於極度的被害妄想之中，並用著我的.Me帳號通訊。
>
> 在舊帳號回復之前，我決定建一個新的Twitter帳號來讓其他人知道這是怎麼一回事。我登入Tumblr並寫下整個經過。在當時，我以為是我的七位數字Apple ID密碼被駭客使用暴力法破解了。在文章回應中，有人猜測駭客使用了某種形式的擊鍵側錄程式。在文章的最後，我留下了我的新Twitter帳號連結。
>
> 然後，攻擊我的其中一名駭客從Twitter發＠訊息給我。在稍後他自稱為Phobia。 我follow了他，他也follow了我。
>
> 我們開始透過Twitter私訊通信，隨後開始透過email以及AIM聯繫。Phobia透露了整個駭客過程中的足夠訊息，讓我確信這的確是他做的。至少，他是其中之一。我同意不提起控訴，而回報是告訴我他究竟是如何入侵我的帳戶。不過首先，他想要澄清的是：
>
> 我並沒有猜測你的密碼或是使用暴力法破解。我有我自己的一套方法來弄到email。
>
> 我問他為何如此作。這是特別針對我嗎？或是這只是為了弄到GIZMODO的Twitter帳戶？不過事實並不是如此，Phobia表示他們並不知道我的帳號有跟GIZMODO的帳號連結，GIZMODO的帳號只是甜頭。他說這個駭客行動只是為了搶到我的三字母Twitter名稱，他們只想要這個。他們只是想拿到這個帳號，把這帳號給搞爆，然後看著他毀滅。
>
> > “I honestly didn’t have any heat towards you before this. i just liked your username like I said before” 
> >
> > 老實說在此之前我根本一點也不在意你，我只是喜歡你的帳號名稱，就如同我之前所說的。
>
> 他透過Twitter私信這樣告訴我。
>
> 在瀏覽過我的帳號之後，駭客們做了一些背景調查。我的Twitter帳號有連結到我的個人網站，在網站上他們找到了我的Gmail信箱。Phobia猜測這個Gmail信箱也是我用來註冊Twitter的信箱，於是他連到了Google的帳號重置頁面。不過他根本沒有真的試著去重置帳號，這只是個偵查任務罷了。
>
> 由於我沒有打開Google的雙重身份認證功能，當Phobia輸入我的Gmail地址後，他就可以看到我設定用來重置Google帳號的備用信箱。雖然Google隱藏了部分的資訊，將許多字母打上了「＊」號，不過仍然留有足夠的字母（來猜出整個信箱），m\****n@me.com。賓果！！
>
> 這就是駭客行動的過程。如果我用的是Apple以外的信箱，或是開啟Gmail的雙重身份認證功能，整個駭客行動就會到此停止。但是由於我用了.Me信箱當成備用信箱，代表著告訴駭客我有一個Apple ID帳號，這也表示我有漏洞可以入侵。
>
> > “You honestly can get into any email associated with apple,”
> >
> > 老實說，你可以進入任何與Apple相關聯的Email。
>
> 而當這一切發生時，這句話似乎非常正確。
>
> 由於他已經有了Email位置，要讓Apple的技術支援人員將我帳號的密碼發給他，需要的就只剩下我的帳單地址，以及我的信用卡卡號末四碼。
>
> 所以，他是如何取得這些關鍵訊息的？他從簡單的開始。透過Whois搜尋我的個人網站domain，他找到了我的帳單地址。如果是沒有domain的人，可以透過Spokeo、WhitePages以及PeopleSmart來搜尋他/她的訊息。
>
> 真正的技巧是在拿到信用卡號碼，不過這是藉由公司的後端系統。Phobia說他有個夥伴執行了這部分的駭客行動，不過他也向我們敘述了這技巧，讓我們可以通過技術支援服務電話時的認證。這出乎意料之外的容易——容易到Wired可以在幾分鐘之內重複利用這個漏洞兩次。
>
> 首先，打電話給Amazon告訴他們你是帳號的擁有者，想要幫帳號增加一個信用卡號碼。所需要的資訊，只有帳號上的名稱、信箱以及帳單地址，之後Amazon就會讓你輸入新的信用卡號碼。（Wired用的號碼，是從用演算法生成假卡號的網站來的）輸入完畢後，掛斷電話。
>
> 接下來，再一次打給Amazon，並告訴他們你無法登入你的帳號。之後提供姓名、帳單地址以及在前一通電話中新輸入的信用卡號碼，Amazon就會讓你將新的信箱加入Amazon帳號中。在這之後，連上Amazon網站，並將密碼重置信件寄到新的信箱中，這樣就可以讓你看到Amazon帳號內的所有信用卡號碼。不過並不是完整的號碼，只有末四碼。
>
> 但是，就如同我們所知的，Apple也只需要那最後末四碼。

根據Mat Honan的說法，其實整個安全漏洞很大的一部分，是在Amazon與Apple兩家公司，對於同一個資訊在安全上所持的不同看法： 

> The very four digits that Amazon considers unimportant enough to display in the clear on the Web are precisely the same ones that Apple considers secure enough to perform identity verification.
>
> Amazon認為不重要，可以直接顯示在網路上的那四碼，正是Apple認為夠安全，足以驗證身份的那四碼。 

via [How a Hacker Gained Access to a Reporter&#8217;s iCloud Account &#8211; Mac Rumors](http://www.macrumors.com/2012/08/06/how-a-hacker-gained-access-to-a-reporters-icloud-account/) and [How Apple and Amazon Security Flaws Led to My Epic Hacking | Gadget Lab | Wired.com](http://www.wired.com/gadgetlab/2012/08/apple-amazon-mat-honan-hacking/)

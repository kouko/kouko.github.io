---
layout: post
title:  "設計的度量衡"
date:   2016-06-10 19:27:32 +0800
category: "Design"
author: "kouko"
---

現代設計有非常非常多的單位相關的名詞，例如最常見的pt、px、dpi、ppi、mdpi、hdpi、@1X、@2x⋯⋯等等。不過最多人問的問題其實是⋯⋯所以這到底是幾公分？

要回答這個問題，也許要先從活字印刷時代的最主要單位——point（pt），開始講起。

## French Point

在16世紀左右，當時印刷師傅並不是使用共通的單位，例如point、inch等來敘述字體的大小，而是針對不同的字體大小分別命名，命名的規則也沒有統一的標準。

有些名稱是基於該尺寸常用的書籍內容，例如常用在古典文學的「Cicero」，或是用於亨利八世訂製的宗教書籍的「Great Primer」；另一些名稱則是為了凸顯字體本身美麗的外觀，例如「Paragon」以及「Nonpareil」。還有諸如「Excelsior」、「Brilliant」、「Diamond」」、「Pearl」、「Agate Ruby」、「Nonpareil」、「Minion」、「Brevier」、「Bourgeois」、「Pica」、「English」、「Paragon」⋯⋯等等。

這樣的命名法雖然可以說是業內術語，但是造成的問題除了單看名稱無法快速是別出字體大小以及相對的尺寸關係之外，分佈在歐陸各城市的鑄字廠對於每個尺寸的詳細定義也不同。即使同樣稱之為Cicero的字體，實際大小也會有些微的出入。

到了17世紀左右，才有人開始嘗試採用標準單位來統一字體大小。

1694年，法國神父Sébastien Truchet在實驗過使用來自銀器製作時使用的單位「Franch line」來測量字體比例，並在當時法國政府負責制定工藝生產標準的委員會Bignon Commission討論過後，公布了第一個印刷用的point單位，後被稱為「Truchet point」。

> Truchet point：
>
> 1 point = 約 0.0074 inch = 約 0.1879 mm

Truchet point可以說是非常精密的單位。但是對於當時的印刷業界來說，如此精密的度量不但沒有必要，而且也不符合當時慣用的字體大小，因此並沒有順利地被業界採用。

到了1737年，法國的鑄字與排版研究者[Pierre Simon Fournier](https://en.wikipedia.org/wiki/Pierre_Simon_Fournier)再次開始提倡以point系統來取代混亂的字體大小命名規則，隨後經過多次改良，在1764年確立了比較完整的point系統，也就是今日我們所說的Fournier point。

Fournier point 以當時的cicero尺寸為基礎，定義了「1 cicero ＝ 12 point」，1 point 大約為現今的0.01375 inch（0.345 mm）。

> Fournier point：
>
> 1 point = 1/12 Cicero = 約 0.345 mm

![Fournier's printed scale of his point system, from Manuel Typographique, Barbou, Paris 1764, enlarged](/img/2016-06-10-design-measure/FournierScale144pts.jpg)
<small>Fournier's printed scale of his point system, from Manuel Typographique, Barbou, Paris 1764, enlarged</small>

雖然Fournier point是為了要標準化字體大小的定義，不過由於當時量尺通常是使用紙張印刷，所以也無法保證正確性。雖然之後試圖製作 240 point的金屬量尺，但是由於各種技術上的問題，普及的速度也相當地緩慢。

1770年，教會印刷師[François-Ambroise Didot](https://en.wikipedia.org/wiki/Didot_family#Fran.C3.A7ois-Ambroise_Didot)改良了Fournier point，重新定義1/72 French Royal inch = 1 point，大約為0.0148 inch（0.3759 mm），被稱為「Didot point」。

> Didot point：
>
> 1 point = 1/12 Cicéro = 1/72 French Royal inch = 約 0.3759 mm

相較於Fournier point，Didot point的尺寸略大。在Fournier Point時代為12 point的Cicero，採用Didot point後卻變成了 11 point左右。因為這類的尺寸差異問題，直到19世紀左右，法國國內的印刷廠仍然繼續採用Fournier Point。

不過隨著時代的演進，Didot point最後成為了歐陸最通用的印刷單位系統。雖然其後陸續出現了更多不同的point定義，但是大多都是將Didot Point轉換為公制基礎的嘗試。

## American point
在歐陸開始提倡印刷單位標準化的這段時間，英美依然是採用傳統的字體大小命名法，直到19世紀後期才開始提倡標準化的單位。

1879年，Nelson Crocker Hawks基於當時的 Pica 為 1/6 inch，而 Nonpareil 剛好為 1/2 Pica 之下，將Nonpareil 定義為 6 point，並進一步地將各種大小名稱用 point定義後，最終提出（按照他自己的說法是「發明」）了自己的point系統。

> Hawks point:
>
> 1 pica = 1/6 inch
>
> 12 point = 1 pica

不過在1886年由ATF（American Type Founders）所制定的美國標準系統中，並沒有採用Hawks的標準，而是採用了基於公制的「Johnson point」。

Johnson Pica 的名稱來自於Lawrence Johnson。他在1883年收購了美國當時最古老的鑄字工廠之一 Binny & Ronaldson（B＆R），在1843年更名為 L. Johnson & Co. ，其後又於1867更名為 MacKellar, Smiths & Jordan（MS&J） ，最終在1892年併入ATF。

B＆R最初創立於1796年，在1806年時向William Duane收購了一些鑄字設備，而這些設備正是Benjamin Franklin在二十多年前在法國時向Pierre Simon Fournier購買的。在經過多年的鑄字誤差後，逐漸成為了Johnson Pica。

而當時美國最古老的鑄字工廠之一 Marder, Luse and Co.，在1871年芝加哥大火災後重建的過程中，也決定開始採用 Johnson Pica。在全美最大的兩家鑄字廠開始使用相同的規格後，Johnson Pica 漸漸地變成了業界的標準規格。

> Johnson point
>
> 1 pica = 35/83 cm = 約 0.1660 inch
>
> 1 point = 1/12 pica = 175/498 mm = 約 0.3514 mm

## DTP時代
DTP（Desktop publishing）一詞，最早是在1986年由Aldus的CEO，Paul Brainerd為了宣傳方便而開始使用的。一開始的DTP系統是由Aldus的排版軟體PageMaker、Apple的Macintosh平台，以及Adobe的頁面描述語言PostScript所組成。相較於之前的電腦排版系統，最大的突破是達成了WYSIWYG（What You See Is What You Get，所見即所得）。

Apple最早開發Macintosh時的目標之一，就是徹底做到WYSIWYG。由於當時美國通行的印刷單位——也就是Johnson系統——的point非常近似1/72 inch，因此Apple決定採用最接近72dpi的螢幕，搭配販售的印表機ImageWriter解析度也設計成72的倍數144dpi，徹底達成了「1 ponit = 1 dot = 1 pixel」的原則。

而Adobe在設計PostScript時，也同樣採用了 1 point = 1/72 inch ，恰好回到了Hawks當年所提出的規格。最終， 1 point = 1/72 inch 變成了大家所說的「DTP point」。

> DTP point:
>
> 1 point = 1/72 inch = 0.3527 mm

### 72ppi & 96ppi
DTP時代最大的優點在於WYSIWYG，但同時也產生了另一個全新的問題 —— 螢幕解析度。

當時IBM PC的螢幕像素密度（pixel pre inch, ppi），大約介於70~74ppi左右。而Macintosh為了符合DTP point，在 1 point = 1 dot = 1 pixel 的原則之下，採用了72ppi的螢幕。但是由於當時慣用的文件內文大小為 10 point，在Macintosh上僅僅只有10 pixel，只算x-height的話差不多只有5 pixel。在此背景之下，許多在Macintosh上的文件都漸漸地開始採用12 point的內文大小。

除了因為像素不足之外，另一個問題發生在螢幕的觀看距離上。傳統在觀看紙本文件時，閱讀距離大約與手臂等長。但是電腦螢幕通常距離更遠，當時經過研究後，大約比一般閱讀距離長約1/3左右。如果要讓人眼觀看到的視覺尺寸相同，代表螢幕上的大小必須比紙本上的尺寸要大才行。

相對於Apple執著於WYSIWYG，Microsoft開始試圖解決視覺尺寸的問題。

Microsoft在Windows上的解決方案，是在軟體層上將72dpi的螢幕當成96dpi。當軟體上要輸出1 pixel時，Windows會先經過轉換，最終輸出 96/72 pixel，大約比原始像素多了1/3左右。之後又IBM推出了96ppi的8514螢幕，Microsoft又配合新增了120ppi的設定。

> Macintosh:
>
> 1 point = 1/72 inch = 72/72 pixel    
>
> Windows:
>
> 1 point = 1/72 inch = 96/72 pixel

雖然看似暫時解決了問題，電腦螢幕的像素密度也大致維持著72ppi左右長達二十多年，不過隨著筆記型電腦以及各種攜帶型裝置的登場，出現了各式各樣尺寸與像素密度的螢幕，問題又再次出現了。

## Mobile時代


via
[Typographic unit - Wikipedia, the free encyclopedia](https://en.wikipedia.org/wiki/Typographic_unit)
, [Where does 96 DPI come from in Windows? fontblog](https://blogs.msdn.microsoft.com/fontblog/2005/11/08/where-does-96-dpi-come-from-in-windows/)

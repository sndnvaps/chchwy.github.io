---
layout: post
published: true
title: 讀書心得--Linux傳奇 (Rebel Code)
categories: 讀書心得
tags: Linux
---

<a href="http://www.anobii.com/books/Linux_%E5%82%B3%E5%A5%87/9789571333632/01703e4119ee4f88ab/" class="book-cover" title="More about Linux 傳奇"><img alt="More about Linux 傳奇" src="http://image.anobii.com/anobi/image_book.php?type=5&amp;item_id=01703e4119ee4f88ab&amp;time=0" style="padding-bottom: 5px; padding-left: 5px; padding-right: 5px; padding-top: 5px;" title="More about Linux 傳奇" /></a>

報導文學的傑作！

回想上一次令我心中同樣湧現出如此激動的書，已經是四五年前讀的『宇宙的寂寞心靈』。這兩本書的共同點就是雖然主題是科學技術，但是卻對人性有深刻的描寫。技術是冰冷的，但是走在大時代洪流中的人，卻是各個有血有肉。

原文書名叫做『Rebel Code』，直譯叫『叛碼』 (吐槽一下糟糕的中文書譯名，尤其副標題比爾蓋茲云云可說完全搞錯方向)。這個書名非常有意思，因為這兒Code是個雙關，一個意思是程式碼，另一個意思是法典。恰恰代表了本書描寫的兩個對象，以Linux為首顛覆傳統開發方式大獲成功的開源軟體，以及一群奔放不羈、充滿理想的平凡人，運用自己的力量搖動世界成為典範的故事。

從自由軟體的開創者Stallman始，到Linux成為一方之霸終，以 Linux 的發展作為主軸，寫成了一個長達十年、可歌可泣的故事。我看著幾個只曾在課本封面上見過名字的資訊大頭們的名字，讀著他們說的話，頓時覺得這些人不再是遙遠天邊的神級人物。如 Linus 與 Tanenbaum 在討論群組上對作業系統設計架構的針鋒相對的大戰，原來這些人口水也很能噴，有趣的緊。

除了Linux之外，著名的開源項目GNU、GCC、Apache、Perl、Mozilla也都在書中占有一定篇幅，本書可以說是一個全面的開放源碼運動的紀錄。

## 大教堂與市集

全書的結構分為兩大段，前八章是 Linux 的成長過程，第十章後則是 Linux 一路攻城掠地。而位居中間的第九章是本書的一個高潮，全章以『大教堂和市集』一文為中心，深入淺出的分析了開源自由軟體成功的原因。

大教堂與市集代表兩種相互衝突的軟體開發觀點，大教堂是傳統的軟體開發觀：

>『我相信最重要的軟體必須如建造一座教堂般，由個別的高手或一小群專家在光輝的孤立中小心翼翼地精雕細琢，時機未到之前，不會釋出測試版。』

但Linux完全顛覆了傳統，來自世界各地的烏合之眾打造了高品質的程式：

>『儘早並經常發表新版本，授權每一件可以委託的事，不拒絕幾乎到混亂程度的程式，...Linux 的同好們似乎組成了喧鬧的大市集，以這個風格發展出來的Linux既一致又穩定，表面上看來真是一連串的奇蹟。』

大教堂和市集深切的探討了Linux成功的原因，並把成功的原因歸納成一系列的格言，每句格言都很有意思，不妨一讀。[大教堂與市集全文](http://www.cui-zy.cn/Recommended/Linux/%E6%95%99%E5%A0%82%E8%88%87%E5%B8%82%E9%9B%86.pdf)

讀完書後，我自己的對開源的一點想法是，其實使用者並不管軟體本身開不開放，真正關心的是軟體到底合不合乎需要。而開放比封閉更容易貼近使用者的需求。每個人都曾經想過「如果OO軟體有XX功能就好了!」而專利軟體最糟糕的一點就是使用者對這個問題幾乎無能為力。開源軟體的架構下，每個人都可以自己動手添加功能或修復錯誤。當使用者同時也是開發者，兩個角色重疊，軟體最麻煩的需求分析的門檻就降到零了。

同時書中提到一個觀點，開源軟體的知識共享可以免去重複造輪子。Linux之前，很多版本的Unix擁技術各據山頭，收取高額權利金，結果因為Unix版本太多，每家公司都要重新開發一次類似的功能，消耗整個軟體界的能量。最後的下場是便宜的Windows NT一來，風吹樹倒，整個Unix伺服器佔有率掉光光。不過本書也說明開源不是萬靈丹，並不是什麼專案開源之後都會成功。

另外一點，Linux的成功與Torvalds本身個性有很大關係。Linux發展之初，其實有兩個開源Unix互相競爭，分別是Tanenbaum撰寫的Minix，以及Torvalds撰寫的Linux。而勝出的關鍵就在Torvalds的個性極為開放，幾乎任何人送來的patch都來者不拒，還鼓勵大家這麼做。反觀Tanenbaum對修改Minix一直機機歪歪，步調緩慢。群眾自然湧向願意聆聽大眾聲音並改變的Linux。

## 駭客精神

另外貫穿於全書之中令人敬佩的 - 駭客精神：把金錢擺到次位，一心追求最好的技術、最好的軟體。重視自由、分享、社群精神，關注軟體的創作、美、以及有趣。我覺得這才是整個開源運動最動人的地方。書中有句話『自由軟體即是關心社會』，讓我會心一笑。

本書出版於2000年左右，至今以過了十載，開源有許多後續發展，像十一章Linux系統採用的版本控制軟體 BitKeeper 終被拋棄，git誕生。2001年時被認為失敗的案例Mozilla，以Firefox之姿浴火重生，現在已經是鋒頭最健的開源項目之一。

最後我真的想說 -- 本書編輯很差，好好一本傑作就這樣被糟蹋，第一次看到書的目錄可以印成這樣糟糕。翻譯品質也很差，翻譯者是資訊外行，很多專門的資訊名詞像GPL、CVS、micro-kernel、CSS、DOM，語句中明顯看的出來譯者自己也不知道在寫什麼，『妙不可言的人月』其實是著名的軟體工程著作『人月神話』，『HTML標識』應該叫『HTML標籤』，眾多關於作業系統內核的字句名詞也錯誤百出，我建議本書的翻譯稿也應該開源一下。

對了，看完本書後，我真的覺得GCC是這個世界上最偉大的軟體之一。


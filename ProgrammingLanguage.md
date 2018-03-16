# Programming Language

## 2018-03-17

  * saemcro:

    > GHC 一到店，所有的 compiler 便都看著他笑，有的叫道，「GHC，你 type system 又添上新 type inference extension 了！」
    >
    > 他不回答，對櫃裡說，「宣告兩個 type family，要一個 higher-kinded polymorphism。」便排出九個 forall。
    >
    > 他們又故意的高聲嚷道，「你一定又多了新的 unsoundness 了！」
    >
    > GHC 睜大眼睛說，「你怎麼這樣憑空污人清白……」
    >
    > 「什麼清白？我前天親眼見你編譯了何家的 code，segmentation fault。」
    >
    > GHC 便漲紅了臉，額上的青筋條條綻出，爭辯道，「type inference 不能算 unsoundness……type inference！……compile-time 的事，能算軟麼？」
    >
    > 接連便是難懂的話，什麼「local type inference」，什麼「Skolem」之類，引得眾人都鬨笑起來：店內外充滿了快活的空氣。
    >
    > #民明書房 - GHC乙己

    原版是[新乙己][M.1521094064.A.488]。

  [M.1521094064.A.488]: https://www.ptt.cc/bbs/joke/M.1521094064.A.488.html

## 2016-09-12

  * erlin 分享了 http://jelv.is/talks/ ，表示他講 types 那邊對閱讀 TaPL 有幫助。

    * 莫忘 TaPL [共筆][TaPL-hackpad]。

  [TaPL-hackpad]: https://hackpad.com/TaPL--y8iYXwtcG1G

## 2016-09-04

  * Bloomberg 推出了 Ocaml to JS 的 [BuckleScript][BuckleScript] 。

  * CindyLinz 在「Re: [討論] 唐鳳真的很有名嗎?很厲害嗎?」串的[某一篇][twowoods]中提到了 au 參與實作了 GADTs 。

    * 是 [2014-07-04][2014-07-04] 23:14:24 親口在頻道上聽 au 說的。

    * b4283 想念了一下 hashcat 。

    * kuanyui 想起 au 在[「函數程式設計的商業應用」][FLOLAC14]中提過 Perl 6 spec 是在實作中釐清的：

      > 所以當我們實際把它實作出來的時候，就發現這個有點像是，如果有看過倚天屠龍記的話，乾坤大挪移如果從第七層練起的那種感受，所以說完全自相矛盾，那個spec裡面看起來寫得非常順的，事實上實作起來完全不是這麼一回事。
      >
      > 所以我們就跟Larry說寫錯了，你這邊跟這邊自相矛盾，然後我們實作出來發現是矛盾的。他說對！好，那太好了，我來擴充spec(笑)。

  [BuckleScript]: https://github.com/bloomberg/bucklescript
  [twowoods]: https://www.ptt.cc/bbs/Soft_Job/M.1472870684.A.962.html
  [2014-07-04]: http://cindy.csie.org/irc.log/haskell.tw/haskell.tw-2014/%23haskell.tw-2014-07-04
  [FLOLAC14]: https://hackpad.com/CUFP-FLOLAC14-PoPV1V9wVse

## 2016-08-21

  * erlin 發現 Soft_Job 版又在[戰遞迴](https://www.ptt.cc/bbs/Soft_Job/M.1471692879.A.0C1.html)了。

    * CindyLinz 分享了自己怎麼靠 stack [想著遞迴寫迴圈][fuzzy_find_gen.h]。

      > 不需要 stack 的話.. 通常會直接用迴圈的思維去想迴圈怎麼寫了  
      > 用到 stack 的話, 心中常常想的是遞迴  
      > 一半一半..  
      > 還有一種是會一次把同一層的 children 都拆出擺在 stack 裡的話.. 那思考的時候還是迴圈不是遞迴  
      > 但這次是每一層都有機會是出去回來以後換個樣子再出去的, 就是用遞迴想的了

  * UncleHandsome 提到 [RednaxelaFX][RednaxelFX] 。

    * 後來 descent 貼了一篇[詢問 JS 的功能是否都由 C/C++ 實現的文章][js_c_cpp]，就是 RednakelFX 回答的。  
      內文甚至提到一個以 JavaScript 實現的 JavaScript 引擎 [Tachyon][Tachyon] 。

  [fuzzy_find_gen.h]: https://github.com/CindyLinz/Perl-Tree-SizeBalanced/blob/master/fuzzy_find_gen.h
  [RednaxelFX]: https://www.zhihu.com/people/rednaxelafx
  [js_c_cpp]: https://www.zhihu.com/question/49176184/answer/116675413
  [Tachyon]: https://github.com/Tachyon-Team/Tachyon

## 2016-08-11

  * descent 分享了他之前關注的[《垃圾回收的算法与实现》](http://www.ituring.com.cn/book/1460)電子書購買連結。

  * 日文原版請見[《ガベージコレクションのアルゴリズムと実装》](https://www.amazon.co.jp/dp/4798025623)， _13h 曾提過「知乎上有中文版的編輯出來說原作者加寫新章節」。

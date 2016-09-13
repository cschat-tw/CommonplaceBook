# C

## 2016-09-09

  * descend 分享的 tinlans 講解有關 library 設計的[心得][policy-based]，提到 GoF  
    的範例大多建立在動態多型的世界， template 實作是立足在靜態多型的世界，並舉例  
    詳細說明兩個世界的需求有多大的差異，警惕後進不要分不清楚使用情境，影響自己的  
    成長。

  [policy-based]: https://www.ptt.cc/bbs/C_and_CPP/M.1473355423.A.378.html

## 2016-09-05

  * descend 提到看到人家寫的 compiler, 都會試試 `char (*(*x[3])())[5]` 這種複雜的宣告。

    * CindyLinz 向 kuanyui 解釋了怎麼樣閱讀 function pointer ：

      > 12:03:59 <CindyLinz> kuanyui_hp: 果然感受到滿滿的惡意了... XD
      > 12:04:28 <CindyLinz> kuanyui_hp: 我覺得先看 function pointer 再回頭看 array 的會比較好懂
      > 12:05:14 <CindyLinz> 其實只是語法很怪, 一部分的 type 寫在 identity 的後面.....
      > 12:05:26 <CindyLinz> int (*)(char, double) 是一個 fun ptr
      > 12:05:40 <CindyLinz> 指向... 吃 char 與 double 以後吐一個 int 的 function
      > 12:05:58 <CindyLinz> 如果同時要寫這個 fun ptr 的 name 的話, 語法是
      > 12:06:03 <CindyLinz> int (*funptr)(char, double)
      > 12:06:57 <CindyLinz> 然後然後, 如果後面的 (char, double) 改成 [5][3] 這樣子像 array size 的東西.. 那麼就變成指向一個大小為 [5][3] 二維陣列的 aryptr
      > 12:07:34 <CindyLinz> 畢竟... 要指向 function, 當然會需要知道一下被指的 function 的參數 type 與 return type?
      > 12:10:39 <CindyLinz> kuanyui_hp: 那個... funptr type 很怪的問題, 可以有一種「只痛一次」的寫法
      > 12:11:02 <CindyLinz> kuanyui_hp: 先 typedef int (*funptr_t)(char, double); 然後就可以 funptr_t my_funptr; 這樣 ^^|

## 2016-09-03

  * CindyLinz 試著<del>拐騙</del>推薦 kuanyui 閱讀 C++ [sp][implicit_conversion] [ec][value_category] 。

  [implicit_conversion]: http://en.cppreference.com/w/cpp/language/implicit_conversion
  [value_category]: http://en.cppreference.com/w/cpp/language/value_category

## 2016-08-20

  * letoh, CindyLinz, descend 討論到 gun99 和 c11 才有的 [unnamed union][unnamed_union] 。

    descend 聊到 long 在 win 32-bit/64-bit 都是 4 bytes ，但 linux 64-bit 下是 8 bytes 。

  [unnamed_union]: https://gcc.gnu.org/onlinedocs/gcc/Unnamed-Fields.html#Unnamed-Fields

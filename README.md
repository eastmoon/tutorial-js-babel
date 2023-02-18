# tutorial-js-babel

## 簡介

**Babel is a JavaScript compiler toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.**

自 1998 年起的第一次[瀏覽器戰爭 ( Browser War )](https://zh.wikipedia.org/zh-tw/%E6%B5%8F%E8%A7%88%E5%99%A8%E5%A4%A7%E6%88%98)以 Internet Explorer 稱霸當時瀏覽器主要市場後的 10 年間，為了追求更好的使用者互動，在此期間 Flash 的 ActionScript 崛起並主宰了這段時間，而跟隨 HTML4 規範的 HTML、JavaScript、CSS 則被市場封存在過往。

直到第二次戰爭開始前，原本退出市場的 Netscape 擁抱開源，並在此期間延伸出 Firefox、Chromium，此時為了更佳的使用者互動而更隨 Internet Explorer 設計的外部軟體 Flash 卻為應對第二次瀏覽器戰爭導致系統的逐漸肥大，為了更好應對此次爭霸的瀏覽器戰國時代，默默推進的腳本語言 ECMAScript 伴隨著 [HTML5](https://zh.wikipedia.org/zh-tw/HTML5) 制定再次回到了世人的目光中。

跟隨 HTML5 規範，使用的 ECMAScript 2015，也稱為 ES6，添加了諸多語法與規範，相較過往 ES3 更加嚴謹且符合[程式語言泛型 ( Programming paradigm )](https://zh.wikipedia.org/zh-tw/%E7%BC%96%E7%A8%8B%E8%8C%83%E5%9E%8B)，然而，此時正值瀏覽器戰國，諸家爭鳴的時期，為了讓新制定的 ECMAScript 規範能相容於舊制瀏覽器，並應對不同時期的瀏覽器支援。

![interpreted-vs-compiled](./img/interpreted-vs-compiled.png)

本是直譯腳本的 JavaScript 便在開發流程中增加編譯流程，使其能有效導入各類程式語言泛型 ( Programming paradigm )，讓 JavaScript 從過往的腳本逐漸成熟成如今廣泛運用的語言；而肩負著 JavaScript 編譯的主要工具，便是本專案討論的 Babel。

Babel 就如其文獻所說，是 JavaScript 編譯器工具，主要用途可分為以下幾項：

+ 句法轉換
+ 補充目標環境缺失的功能特徵
+ 原始碼轉換

由於以上功能，Babel 也可用於將特定框架 ( Framework ) 的語法轉換，已讓其可用於不同的瀏覽器；但需注意，並非所有瀏覽器都支援 ESMASCript 各版本，這也意味不同框架與工具底層可使用的 ECMAScript 版本需依據產品預期對應的瀏覽器進行選擇，避免產品若入系統破碎化的陷阱。

以 Node.js 基礎使用 V8 引擎為範例，若要確認 Node.js 可適用的 ECMASCript 範圍，可參考 [node.green](https://node.green/) 的列表。

## 範例

本專案執行的範例：

+ 使用 Node.js 18+ LTS 版本
+ 應對不同 Babel 版本

## 執行

本專案使用的命令介面僅適用 Windows 環境且運行於 Docker 環境。

+ 指定進入 Babel 7 開發環境

```
babel dev --ver=7
```

## 文獻

+ [Babel](https://babeljs.io/docs/en/)
    - [Babel.js - wiki](https://zh.wikipedia.org/zh-tw/Babel_(%E7%B7%A8%E8%AD%AF%E5%99%A8))
    - [ECMAScript](https://zh.wikipedia.org/zh-tw/ECMAScript)
+ [Node.js](https://nodejs.org/en/)
    - [Node.js - wiki](https://zh.wikipedia.org/zh-tw/Node.js)
    - [npm.js](https://docs.npmjs.com/cli/v7/commands)

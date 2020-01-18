# [rgb2hex: RGB to Hex Color Code Tool](https://laiyenju.github.io/rgb2hexcode/)

[This](https://laiyenju.github.io/rgb2hexcode/) is a webpage helping you to understand how **RGB Color Code** transforms to **Hex Color Code**.

> **Referenced**
> -   [Harvard CS50 Web 的 JavaScript 影片](https://cs50.harvard.edu/x/2020/tracks/web/)
> -   [動動手來學 Regular Expression 正規表達式](https://5xruby.tw/posts/learn-regular-expression/) by 五倍紅寶石
> -   [別再只會複製貼上！帶你真正搞懂 Hex Color Codes](https://5xruby.tw/posts/understand-hex-color-codes/) by 五倍紅寶石，提供專案靈感
> 
> **Difficulties**
> 1.  如何抓取到使用者輸入的 RGB 編碼，再存成 Hex 顏色編碼要使用的變數。
> 2.  如何在使用者輸入編碼的同時，讓背景顏色隨之改變（監聽輸入事件）。


### Webpage :point_down: 
The interface is inspired by [Panton](https://store.pantone.com/hk/en/?gclid=EAIaIQobChMIs-6406iL5wIVQXRgCh2jMQ8jEAAYASAAEgIO4fD_BwE).

![](https://i.imgur.com/uB31gAK.png)

### Input the R, G, B value :point_down: 
When user inputs the value, the Hex Color Code at the bottom and the background color will change simultaneously. 

User can easily compare the R, G, B's values along with the Hex Color Code and the background color.

![](https://i.imgur.com/XUcHN0r.png)

### What I Learn in this project
- [Regular Expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
Hex color code is a 6 digit combination of numbers and A to F alphabet. In order to verify the input value, I use regular expression to check the input value and remind user.
- `document.getElementById` to catch DOM element.
- `document.getElementById("r1").value;` transform the input, id is r1, to value.
- `var hexcode = '#' +r1 + r2 + g1 + g2 + b1 + b2;` combine all the input text to Hex Color Code.
- `document.body.style.background` change the background style.

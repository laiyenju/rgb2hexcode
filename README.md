# RGB to Hex Color Code Tool

This is a webpage helping you to understand how **RGB Color Code** transforms to **Hex Color Code**.

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

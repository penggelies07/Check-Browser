# Check-Browser


&emsp;&emsp;最近有个需求:判断浏览的入口，最常用的是判断微信端和QQ端还有微博端的内置浏览器。后来觉得反正都写了手机端的，要不就来个总和吧，把各大浏览器都判断一次，方便日后使用。  

&emsp;&emsp;基本原理是根据浏览的一个属性

```JavaScript
navigator.userAgent;

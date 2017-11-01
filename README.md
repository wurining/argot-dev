# argot-dev “黑话”集锦
>💡集合Web开发中的名词翻译，欢迎踊跃提issue出来。

>💡创建这个项目为了尽可能解决一些开发者不太清楚“行话”，但是又很难准确的了解它的问题。

>💡项目灵感来自于文章[《Web开发中的“黑话”》](https://segmentfault.com/a/1190000002593432)

>💡为了尊重原文作者，把Polyfill和Vanilla JavaScript放在第一的位置。

# 2017年11月01日
## Polyfill
* `Polyfill`的准确意思为：用于实现浏览器并不支持的原生API的代码。来自网络解释：`Polyfilla`是一个英国产品,在美国称之为`Spackling Paste`(译者注:刮墙的,在中国称为腻子).记住这一点就行:把旧的浏览器想象成为一面有了裂缝的墙.这些`polyfills`会帮助我们把这面墙的裂缝抹平,还我们一个更好的光滑的墙壁(浏览器)。例如，`querySelectorAll`是很多现代浏览器都支持的原生`Web API`，但是有些古老的浏览器并不支持，那么假设有人写了库，只要用了这个库， 你就可以在古老的浏览器里面使用`document.querySelectorAll`，使用方法跟现代浏览器原生API无异。那么这个库就可以称为`Polyfill`或者`Polyfiller`。

## Vailla JavaScript
* `Vailla JavaScript` 是目前世界上跨平台兼容性最好、最小、最快的JavaScript框架。它的官网为：http://vanilla-js.com/
* 看过官网后你就懂了，实际上这个网站跟你开了个大玩笑，所谓快速，轻量，跨平台不过就是原生`JavaScript`!🤣

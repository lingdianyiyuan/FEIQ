# rem,rpx,vw是什么？vw和rem的区别?

## rem是什么？

​	rem 是（font size of the root element），官方解释意思就是根据网页的根元素来设置字体大小，和 em（font size of the element）的区别是，em 是根据其父元素的字体大小来设置，而 rem 是根据网页的跟元素（html）来设置字体大小的，举一个简单的例子.

现在大部分浏览器 IE9+，Firefox、Chrome、Safari、Opera ，如果我们不修改相关的字体配置，都是默认显示 font-size 是 16px 即

```html
html {
    font-size:16px;
}
```

那么如果我们想给一个 P 标签设置 12px 的字体大小那么用 rem 来写就是

```html
p {
    font-size: 0.75rem; //12÷16=0.75（rem）
}
```

rem对浏览器的支持

![rem](https://github.com/lingdianyiyuan/FEIQ/blob/master/images/rem.jpg)

数据来自https://caniuse.com/#feat=rem

这个单位代表根元素的 [`font-size`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-size) 大小（例如 <html>元素的font-size）。当用在根元素的[`font-size`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-size)上面时 ，它代表了它的初始值

设置根元素-相对于根元素`html`

```html
html {
	font-size: 100px;
} //100px方便计算，实际值需要自己确定
```

## rpx是什么？

rpx是微信小程序WXSS的尺寸单位。介绍rpx前，先要介绍WXSS。

### WXSS

WXSS（Weixin Style Sheets）是一套样式语言，用于描述WXML的组件样式。

WXSS用来决定WXML的组件应该怎么显示。

为了适应广大的前端开发者，WXSS具有CSS大部分特性。同事为了更适合微信小程序，WXSS对CSS进行了扩充以及修改。

与CSS相比，WXSS扩展的特性有：

- 尺寸单位
- 样式导入

#### 尺寸单位

rpx（responsive pixel）:可以根据屏幕宽度进行自适应。规定屏幕为750rpx。如在iPhone6上，屏幕宽度为375px，共有750个物理像素，则750rpx=375px=750物理像素，1rpx=0.5px = 1物理像素。

| 设备         | rpx换算px (屏幕宽度/750) | px换算rpx (750/屏幕宽度) |
| ------------ | ------------------------ | ------------------------ |
| iPhone5      | 1rpx = 0.42px            | 1px = 2.34rpx            |
| iPhone6      | 1rpx = 0.5px             | 1px = 2rpx               |
| iPhone6 Plus | 1rpx = 0.552px           | 1px = 1.81rpx            |

**建议：** 开发微信小程序时设计师可以用 iPhone6 作为视觉稿的标准。

**注意：** 在较小的屏幕上不可避免的会有一些毛刺，请在开发时尽量避免这种情况。

参考资料：[微信官方文档·小程序](https://developers.weixin.qq.com/miniprogram/dev/framework/view/wxss.html)

## vw是什么？

viewpoint width，视窗宽度，1vw=视窗宽度的1%,假如浏览器的宽度为200px，那么1vw就等于2px（200px/100）。

## vw和rem的区别?

rem根据网页的根元素来设置字体大小，vw是视窗的宽度。
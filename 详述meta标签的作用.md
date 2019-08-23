# 详述meta标签的作用

meta标签是html语言头部的一个辅助性标签，提供有关页面的元信息（比如：针对搜索引擎和更新频度的描述和关键词，定义页面的使用的语言），使用好<meta>标签对heml很有益。

meta标签共有两个属性，他们分别是http-equiv属性和name属性，不同的属性有不同的参考值，这些不同的参数值实现了不同的网页功能。

## name属性：

name属性主要用于描述网页，与之对应的属性值为content，content中的内容主要是便于搜索引擎机器人查找信息和分类信息用的。

meta标签的name属性语法格式是：<meta name="c参数" content="具体的参数值“>

## http-equiv属性：

equiv的全称是”equivalent“相当于的意思，类似于HTTP的头部协议，它回应给浏览器一些有用的信息，以帮助正确和精确地显示网页内容，实际取值由content决定



```html
<head>
    //name属性
    <meta charset="UTF-8">
    //定义文档的字符编码
	<meta name="description" content="详述meta标签的作用">
    //定义web页面描述
	<meta name="keywords" content="详述meta标签的作用">
    //定义文档关键词，用于搜索引擎
	<meta name="author" content="零点一元">generator
    //定义作者
    <meta name="generator" content="Dreamweaver">
    //指定文档生成的工具名称
	<meta name="robots" content="none">
    //robots用来告诉搜索机器人那些页面需要引索，那些页面不需要引索
    
    //http-equiv属性
    <meta http-equiv="expires" content="Fri, 12 Jan 2001 18:18:18 GMT">
    //可以用于设定网页的到期时间。一旦网页过期，必须到服务器上重新传输。必须使用GMT的时间格式。
    <meta http-equiv="Refresh" content="2；URL=http://www.y-clay.com">
    //自动刷新并指向新页面
     <meta http-equiv="Set-Cookie" content="cookievalue=xxx; expires=Friday, 12-Jan-2001 18:18:18 GMT； path=/">
    //如果网页过期，那么存盘的cookie将被删除
    <meta http-equiv="Window-target" content="_top">
    //强制页面在当前窗口以独立页面显示。
    <meta http-equiv="content-Type" content="text/html"; charset="gb2312">
    //设定页面使用的字符集
</head>
```


# 用css选择列表中的第二项

*选择列表中的第二项：li:nth-child(2)*

## 基本选择器

### 	通配符选择器（*）

​			通用元素选择器，匹配任何元素

### 	标签选择器（div,h1,p）

​			标签选择器，匹配所有使用此标签的元素

### 	类选择器（.info）

​				class选择器，匹配所有class属性中包含info的元素

### 	id选择器（#footer）

​					id选择器，匹配所有id属性等于footer的元素

## 多元素的组合选择器

### 		多元素选择器（E，F）

​					多元素选择器，同时匹配所有E元素或F元素，E和F之间用逗号分隔

### 		后代元素选择器（E F）

​					后代元素选择器，匹配所有属于E元素后代的F元素，E和F之间用空格分隔

### 		子元素选择器（E>F）

​					子元素选择器，匹配所有E元素的子元素F

### 		毗邻元素选择器（E+F）

​					毗邻元素选择器，匹配所有紧随E元素之后的同级元素F

## 属性选择器

### 		E[att]

​				匹配所有巨有att属性的E元素，不考虑它的值。（注意：E在此处可以省略，比如“[cheackend]”。以下同。

### 		E[att=val]

​					匹配所有att属性等于“val"的E元素。

### 		E[att~=val]

​					匹配所有att属性具有多个空格分隔的值、其中一个值等于”val"的E元素。

### 		E[att|=val]

​					匹配所有att属性巨有多个连字号分隔（hyphen-separated）的值、其中一个值以“val”开头的E元素，主要用于lang属性，比如“en”、"en-us"、"en-gb"等等

## CSS2.1中的伪类

### 		E:first-child

​					匹配父元素的第一个子元素

### 		E:link

​					匹配所有未被点击的链接

### 		E:visited

​					匹配多有已被点击的链接

### 		E:active

​					匹配鼠标已经其上按下、还没又释放的E元素

### 		E:hover

​					匹配鼠标悬停旗上的E元素

### 		E:focus

​					匹配获得当前焦点的E元素

### 		E:lang(c)

​					匹配lang属性等于c的E元素

## CSS2.1中的伪元素

### 		E:first-line

​					匹配E元素的第一行

### 		E:firsr-letter

​					匹配E元素的第一个字母

### 		E:before

​					在E元素之前插入生成的内容

### 		E:after

​					在E元素之后插入生成的内容

## CSS3的同级元素通用选择器

### 		E~F

​					匹配任何元素在E元素之后的同级F元素

## CSS3属性选择器

### 		E[att^="val"]

​					属性att的值以“val”开头的元素

### 		E[att$="val"]

​					属性att的值以”val“结尾的元素

### 		E[att*="val"]

​					属性att的值包含”val“字符串的元素

## CSS3中与用户界面有关的伪类

### 		E:enabled

​					匹配表单中激活的元素

### 		E:disabled

​					匹配表单中禁用的元素

### 		E:checked

​					匹配表单中被选中的radio（单选框）或checkout（复选框）元素

### 		E::selection

​					匹配用户当前选中的元素

## CSS3中的结构性伪类

### 		E:root

​					匹配文档的根元素，对于HTML文档，就是HTML元素

### 		E:nth-child(n)

​					匹配其父元素的第n个子元素，第一个编号为1

### 		E:nth-last-child(n)

​					匹配其父元素的倒数第n个子元素，第一个编号为1

### 		E:nth-of-type(n)

​					与:nth-child()作用类似。但是仅匹配使用同种标签的元素

### 		E:nth-last-of-type(n)

​					与:nth-last-child()作用类似。但是仅匹配使用同种标签的元素

### 		E:last-child

​					匹配父元素的最后一个子元素，等同于:nth-last-child(1)

### 		E:first-of-type

​					匹配父元素下使用同种标签的第一个子元素，等同于:nth-of-type(1)

### 		E:last-of-type

​					匹配父元素下使用同种标签的最后一个子元素，等同于:nth-last-of-type(1)

### 		E:only-child

​					匹配父元素下仅有的一个子元素，等同于：first-child ：last-child 或：nth-child(1):nth-last-child(1)

### 		E:only-of-type

​					匹配父元素下使用同种标签的唯一一个子元素，等同于:first-of-type :last-of-type或:nth-of-type(1):nth-last-of-type(1)

### 		E:empty

​					匹配一个不包含任何子元素的元素，注意，文本节点也被看作子元素

## CSS3的反选伪类

### 		E:not(s)

​					匹配不符合当前选择器的任何元素

## CSS3中的:target伪类

### 		E:tarfget

​					匹配文档中特定”id“点击后的效果










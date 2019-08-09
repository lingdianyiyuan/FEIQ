# 列举几个css中可继承和不可继承的元素

## 不可继承的：

​	display：display 属性规定元素应该生成的框的类型。

​	margin：margin 简写属性在一个声明中设置所有外边距属性。该属性可以有 1 到 4 个值。

​	border：border 简写属性在一个声明设置所有的边框属性。

​	padding：padding 简写属性在一个声明中设置所有内边距属性。

​	background：background 简写属性在一个声明中设置所有的背景属性。

​	height：height 属性设置元素的高度。

​	min-height：min-height 属性设置元素的最小高度。

​	max-height：max-height 属性设置元素的最大高度。

​	width：width 属性设置元素的宽度。

​	min-width：min-width 属性设置元素的最小宽度。

​	max-width：min-width 属性设置元素的最大宽度。

​	overflow：overflow 属性规定当内容溢出元素框时发生的事情。

​	position：position 属性规定元素的定位类型。

​	left：left 属性规定元素的左边缘。该属性定义了定位元素左外边距边界与其包含块左边界之间的偏移。

​	right：right 属性规定元素的右边缘。该属性定义了定位元素右外边距边界与其包含块右边界之间的偏移。

​	top：top 属性规定元素的顶部边缘。该属性定义了一个定位元素的上外边距边界与其包含块上边界之间的偏移。

​	bottom：bottom 属性规定元素的底部边缘。该属性定义了定位元素下外边距边界与其包含块下边界之间的偏移。

​	z-index：z-index 属性设置元素的堆叠顺序。拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面。

​	float：float 属性定义元素在哪个方向浮动。以往这个属性总应用于图像，使文本围绕在图像周围，不过在 CSS 中，任何元素都可以浮动。浮动元素会生成一个块级框，而不论它本身是何种元素。	

​	clear：clear 属性规定元素的哪一侧不允许其他浮动元素。

​	table-layout：tableLayout 属性用来显示表格单元格、行、列的算法规则。

​	vertical-align：vertical-align 属性设置元素的垂直对齐方式。

## 所有元素可继承：

​		visibility：visibility 属性规定元素是否可见。

​		ursor：cursor 属性规定要显示的光标的类型（形状）。

## 内联元素可继承:

​	letter-spacing：letter-spacing 属性增加或减少字符间的空白（字符间距）。

​	word-spacing：word-spacing 属性增加或减少单词间的空白（即字间隔）。

​	white-space：white-space 属性设置如何处理元素内的空白。

​	line-height：line-height 属性设置行间的距离（行高）。

​	color：color 属性规定文本的颜色。

​	font：font 简写属性在一个声明中设置所有字体属性。

​	font-family：font-family 规定元素的字体系列。

​	font-family 可以把多个字体名称作为一个“回退”系统来保存。如果浏览器不支持第一个字体，则会尝试下一个。也就是说，font-family 属性的值是用于某个元素的字体族名称或/及类族名称的一个优先表。浏览器会使用它可识别的第一个值。

​	有两种类型的字体系列名称：

- 指定的系列名称：具体字体的名称，比如："times"、"courier"、"arial"。
- 通常字体系列名称：比如："serif"、"sans-serif"、"cursive"、"fantasy"、"monospace"

**提示：**使用逗号分割每个值，并始终提供一个类族名称作为最后的选择。

​	font-size：font-size 属性可设置字体的尺寸。

​	font-style：font-style 属性定义字体的风格。

​	font-variant：font-variant 属性设置小型大写字母的字体显示文本，这意味着所有的小写字母均会被转换为大写，但是所有使用小型大写字体的字母与其余文本相比，其字体尺寸更小。

​	font-weight：font-weight 属性设置文本的粗细。

​	text-decoration：text-decoration 属性规定添加到文本的修饰。

​	text-transform：text-transform 属性控制文本的大小写。

​	direction：direction 属性规定文本的方向 / 书写方向。

## 终端块元素可继承：

​	text-indent：text-indent 属性规定文本块中首行文本的缩进。

​	text-align：text-align 属性规定元素中的文本的水平对齐方式。

## 列表元素可继承:

​	list-style：list-style 简写属性在一个声明中设置所有的列表属性。

​	list-style-type：list-style-type 属性设置列表项标记的类型。

​	list-style-position：list-style-position 属性设置在何处放置列表项标记。

​	list-style-image：list-style-image 属性使用图像来替换列表项的标记。
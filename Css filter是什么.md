# Css filter是什么？

filter属性定义了元素（通常是<img>）的可视效果（例如：模糊与饱和度）。

```html
img {
    -webkit-filter: grayscale(100%); /* Chrome, Safari, Opera */
    filter: grayscale(100%);
}
```

使用filter的效果

![filter-0](https://github.com/lingdianyiyuan/FEIQ/blob/master/images/filter-0.jpg)

未使用filter的效果

![filter-1](https://github.com/lingdianyiyuan/FEIQ/blob/master/images/filter-1.jpg)

JavaScript的语法：object*.style.WebkitFilter="grayscale(100%)" 

滤镜通常使用百分比 (如：75%), 当然也可以使用小数来表示 (如：0.75)。


<div> <span>   这两种标签都是布局用的  , 这种标签本身没有任何显示效果, 通常是用来结合css进行页面布局 

# div布局

```html
<div style="margin-left:50px"><!--离左边界50px--><img src="1.jpg"></div>
<div align="right" style="margin-right:50px"><!--离右边界50px--><img src="1.jpg"></div>
```

 这里使用了[style外边距样式](https://how2j.cn/k/css2/css2-margin/248.html)，margin-left:50px 指的是左边距50个像素  需要对两个图片进行左边距控制 

 如果不使用div,则需要对每一个图像设置边距  使用了div后，先把两个图像都放在一个div里  只需要设置div的边距，就可以达到两个图片都移动的效果

# div和span的区别

div是块元素，即自动换行  常见的块元素还有<h1>,<table>,<p>

span是内联元素，即不会换行  常见的内联元素还有<img>,<a>,<b>,<strong> 
# CSS3的选择器

> CSS3添加了一些选择器，有属性选择器、结构性选择器


### 属性选择器


* ele[attr]                 
 元素包含属性attr
* ele[attr="val"]           
 元素的attr值是val
* ele[attr~="val"]          
 元素的attr值中有一个是val值
* ele[attr^="val"]          
 元素的attr值的开头是val
* ele[attr$="val"]          
 元素的attr值的结尾是val
* ele[attr*="val"]          
 元素的attr值中包含了val字符
* ele[attr|="val"]          
 元素的attr值以 val- 开头


### 结构性伪类选择器

> 伪类选择器
* a:link
* a:visited
* a:hover
* a:active

>* ele:focus

> 伪元素选择器

* ele:before
* ele:after
* ele:first-line     伪元素选择器(选中元素的第一行文本)
* ele:first-letter

> 结构性伪类选择器
* ele:root()               等同于html元素
* ele:not()
* ele:empty()
* ele:target()



* ele:first-child           第一个
* ele:last-child            最后一个
* ele:nth-child(num)        从前面数第num个
* ele:nth-last-child(num)   从后面数第num个
* ele:only-child            其父元素有唯一的子元素

* ele:nth-of-type(num)      选择那些和ele同类的元素
* ele:nth-last-of-type(num)






## UI元素伪类选择器

> 
* ele:hover
* ele:active                激活
* ele:default
* ele:enabled               可用
* ele:disabled              不可用
* ele:checked               被选中
* ele:read-only
* ele:read-write
* ele:indeterminate
* ele::selection            被选中或高亮状态




## 文字文本属性

> text-shadow 文字阴影

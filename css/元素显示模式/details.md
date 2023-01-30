# 元素显示模式
元素就是标签就是 <>

## 块级元素
显示特点:
1.独占一行（一行只能显示一个）
2.宽度默认是父元素的宽度，高度默认是由内容撑开
3.可以设置宽高

代表标签:
div、p、h系列、ul、li、dl、dt、dd、form、header、nav、footer

F12 显示 block

## 行内元素
显示特点:
1.一行可以显示多个
2.宽度和高度默认由内容撑开
3.不可以设置宽高

代表标签:
a、span、b、u、i、s、strong、ins、em、del....

F12 显示 inline

## 行内块元素
显示特点:
1.一行可以显示多个
2.可以设置宽高

代表标签:
input、textarea、button、select....
特殊情况: img 标签有行内块元素特点，但是Chrome调试工具显示结果是inline

F12 显示 inline-block

## 元素显示模式转换
改变元素默认的显示特点，让元素复合布局要求
语法:
属性                    效果            使用频率
display:block         转换成块级元素        较多
display:inline-block    转换成行内块元素    较多
display:inline          转换成行内元素      极少
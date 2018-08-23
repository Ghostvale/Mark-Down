# **超链接**

### 1. 行内式：\[link text](URL 'title text')

> 普通链接：\[google](http://www.google.com/ "google")

> 本地文件链接: \[图片](./18081116.jpg)

### 效果：

> 普通链接：[google](http://www.google.com/ "google")

> 本地文件链接: [图片](./18081116.jpg)

### *REMARK：*
1. title部分可加可不加
2. title的引号可以用“”或者‘’

---------
<br><br>

### 2.参考式：
### 一. \[link text][标志符]   
### 二. \[标志符]: URL "title text"

> 普通链接:  [google][1]  
> 本地文件链接: [图片][2]
>  
> \[1]: http://www.google.com "google"  
> \[2]: ./18081116.jpg 

### 效果：

> 普通链接:  [google][1]  
> 本地文件链接: [图片][2]
>  
> [1]: http://www.google.com "google"
> [2]: ./18081116.jpg 

### *REMARK：*
1.标记符的链接部分不能出现在和前一部分同一区块内，但可以在文件的其他任何位置
2.第二个方括号的标志符，可以是空格，数字，字母和符号，注意*不区分大小写*
3.参考式的优点是可以在不同位置引用同一个链接
4.标记符的链接部分也可以用\<>包括起来，title也可以用“”和‘’


---------
<br><br>

### 3. 被<>包括起来的URL和邮箱地址会自动转化为超链接 

> \<http://www.google.com>  
> \<myemail@email.com>

### 效果：

> <http://www.google.com>  
> <myemail@email.com>

---------
<br><br>
###  [返回目录](./README.md)


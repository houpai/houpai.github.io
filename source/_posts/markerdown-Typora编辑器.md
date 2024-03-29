---
title: markerdown-Typora编辑器
date: 2021-04-12 14:47:26
tags:
- Markerdown
categories:
- 开发工具
---
Typora 是一款支持实时预览的 Markdown 文本编辑器

<!--more-->

## 一 了解Markdown

![img](https://www.runoob.com/wp-content/uploads/2019/03/iconfinder_markdown_298823.png)

Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。

Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。

Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。

Markdown 编写的文档后缀为 **.md**, **.markdown**。

更多详细内容可参照[菜鸟教程:Markdown](https://www.runoob.com/markdown/md-tutorial.html)

## 二 书写工具

Typora官方网站:[https://www.typora.io/](https://www.typora.io/)

Typora中文网站:[https://www.typora.net/](https://www.typora.net/)

国内码云上的发行版本:[https://gitee.com/typora-mirror/Typora-Mirror/releases](https://gitee.com/typora-mirror/Typora-Mirror/releases)

## 三 语法

#### 1. 字体编辑

##### 1.1 标题

```text
# 一级标题        快捷键Ctrl+1

## 二级标题       快捷键Ctrl+2

### 三级标题      快捷键Ctrl+3

#### 四级标题     快捷键Ctrl+4

##### 五级标题    快捷键Ctrl+5

###### 六级标题   快捷键Ctrl+6
```

`三级标题 快捷键Ctrl+3`

##### 1.2 字体大小

```text
快捷键：Ctrl+数字  或 Ctrl+加减号  或  ### （几个#表示几级标题，同上）
```

##### 1.3 字体加粗

```text
快捷键：Ctrl+b
示 例：**加粗内容**
```

##### 1.4 斜体

```text
快捷键：ctrl+i
示 例：*斜体*
```

##### 1.5 删除线

```text
快捷键：alt+shift+5
示 例：~~删除的内容~~
```

##### 1.6 下划线

```text
快捷键：Ctrl+u
示 例：<u>下划线内容</u>
```

##### 1.7 文本居中

```text
操作：<center>居中内容</center>
```

##### 1.8 脚注

```text
操作：这块有个脚注[^脚注]
     [^脚注]:填写脚注的内容
示例：有一个github网址[^1]
     [^1]:https://github.com/
```

注意：使用1.9~1.11功能前，请先在 文件 - > 偏好设置 中的Markdwn中勾选对应的功能，然后重启软件，就可以用了，操作如下图所示

![img](https://pic1.zhimg.com/80/v2-ef6d571b0f47c9e4fc20b7f2dee47a68_720w.jpg)

##### 1.9 上标

```text
使用这个特性，请先在文件 -> 偏好设置 中的Markdwn选择开启。
操作：^ + 字体 + ^
示例：X^2^
```

##### 1.10 下标

```text
操作：~ + 字体 + ~
示例：H~2~O
     X~long\ text~
```

##### 1.11 文字高亮

```text
操作：==高亮文字==
```

#### 2. 列表

##### 2.1 有序列表

```text
操作：数字+英文小数点(.)+空格
示例：1. list1
     2. list2
```

##### 2.2 无序列表

```text
操作：- +空格 或 * + 空格
示例： - list1
      - list2
```

#### 3. 插入

##### 3.1 插入代码块

```text
快捷键：shift+~~~
```

##### 3.2 插入数学公式

```text
操作：$$ + enter
示例：$$ + enter后输入11+12，结果如下所示
```

##### 3.3 插入引用

```text
操作：> + 空格
示例：> + 空格后，输入 引用的内容，结果如下所示
 
```

##### 3.4 插入链接

```text
操 作:Ctrl+k弹出后，输入 [输入标题名](输入链接地址) 即可
示 例1：[百度一下，你就知道](https://www.baidu.com/)
示 例2：这是 [百度一下，你就知道](https://www.baidu.com/ "百度") 的链接.  
示 例3：这是 [github][1] 的链接.  
       [1]: https://github.com/ "github"
ps：按住ctrl点击链接可直接打开
```

##### 3.5 插入注释

```text
操作：[^文字]：文字
示例：[^1]：文献1
```

##### 3.6 插入表格

```text
快捷键：ctrl+t
示 例：按完快捷键后，弹出下图，选择对应的行和列，点击确定即可。
```

![img](https://pic2.zhimg.com/80/v2-f44eb3bc4a5a55951c7efcb2eb11f72d_720w.jpg)

##### 3.7 插入图片

```text
操作：直接拖动  或 ctrl+shift+i(相对路径地址)
示例：![](C:\1.jpg)
```

##### 3.8 插入分隔符

```text
操作：--- + enter  或者 *** + enter
```

##### 3.9 插入表情

```text
操作： ：+ 单词 +:
示例： :smile:
      :cry:
```

##### 3.10 插入目录

操作：[toc]+enter

##### 3.11 公式内换行

操作：\\

##### 3.12 公式内左对齐

操作：在公式最开始加\begin{aligned}，然后每个等号前加&，即&=，每一行用\\换行，然后最后一句输完后\end{aligned}

实例：\begin{aligned}d(x,y)&=\sqrt{(x_1-y_1)^2+(x_2-y_2)^2+\dots+(x_n-y_n)^2}\\&=\sqrt{\sum_{i=1}^{n}{(x_i-y_i)^2}} \end{aligned}

公式如下：

![](https://fastly.jsdelivr.net/gh/tangyuxian/blog_image@latest/PicGo/20210324155609.png)

##### 3.13 矩阵表示

操作：`\begin{matrix}`和`\end{matrix}`说明在它们之间的是矩阵
`1 & 2 & 3\\`表示第一行的元素，其中用`&`来分割每一个元素，用`\\`来换行
实例: \left[\begin{matrix} 1 & 2 & 3\\ 4 & 5 & 6 \end{matrix}\right]

![](https://raw.githubusercontent.com/tangyuxian/blog_image/master/PicGo/20210324155643.png)

##### 3.14 希腊字母表示

![img](https://pic3.zhimg.com/80/v2-68922903c83e504e3e3e4efd5b7327fa_720w.jpg)

##### 3.15 箭头表示

![img](https://pic3.zhimg.com/80/v2-42ff8eb3a827056b16b2133f58009abe_720w.jpg)



##### 3.16 公式大全

![img](https://pic2.zhimg.com/80/v2-2f57dd9499cba748a39be06d2104fe21_720w.jpg)

##### 3.17 二进制运算/相关符号

![img](https://pic3.zhimg.com/80/v2-fd7827f7c554e1f2c6d9a356f868a0fe_720w.jpg)

##### 3.18 空格表示

在公式中如果需要有空格，可以用\+空格的方式来实现

实例：max \ a

##### 3.19 花括号表示

为了美观，常用公式中可能会用到花括号

实例：c(u)=\begin{cases} \sqrt\frac{1}{N}，u=0\\ \sqrt\frac{2}{N}， u\neq0\end{cases}

结果展示如下：

![[公式]](https://www.zhihu.com/equation?tex=c%28u%29%3D%5Cbegin%7Bcases%7D+%5Csqrt%5Cfrac%7B1%7D%7BN%7D%EF%BC%8Cu%3D0%5C%5C+%5Csqrt%5Cfrac%7B2%7D%7BN%7D%EF%BC%8C+u%5Cneq0%5Cend%7Bcases%7D+)

------

语法来源:[知乎文章:Typora的安装和语法](https://zhuanlan.zhihu.com/p/90561228)

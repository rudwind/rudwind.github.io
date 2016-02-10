---
author: rudwind
date: 2016-2-11 04:20+08:00
layout: post
title: Markdown使用方法介绍
slug: markdownexample
categories: 
- 文档教程
tags:
- Markdown
- Markdown教程
---


## 排版介绍

这是一个段落. **这些文本是粗体** 这些文本是正常 _这些文本是斜体_ 我们也可以结合使用他们 **_这些文本既是粗体又是斜体_** 高亮代码这样使用 `ThisIsMyCode()` 这些文本带 [下划线](#) 或是超链接 [http://www.example.com](http://www.example.com).

___

## Headings H1 to H6

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

___

## 脚注

如果你有文章中的一些内容需要提及到一些脚注，请参考如下方式。 
这里是第一个脚注符号的例子 [^1]。这里是第二个脚注符号的例子。[^2]，点击脚注符号可以到达文章末尾的脚注文本。

___

## 块引用

> The roots of education are bitter, but the fruit is sweet. --Aristotle

___

## 列表项

1. 第一项 有序列表使用数字
* 从第二项开始 可以使用数字也可以使用无序列表符号

___

* 无序列表可以使用*号
- 或者-号
+ 或者+号
___

## 代码块

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

___


## 表格

### 表格 1: 对齐方式演示

| 左对齐       | 居中对齐           | 右对齐  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | ok? |
| col 2 is      | centered      |   Got it? |
| col 1 is      | left-aligned  |   Alright!!! |

### 表格 2: 元素排版演示

斜体字 | 代码高亮 | 粗体字
--- | --- | ---
*I* | `am` | **row**
1 | two | III

___

## 水平线

HTML元素 `<hr>` 可以在段落内创建一条 "水平线"。 在 markdown 
中， 我们可以这样使用 `<hr>` 元素：

* `___`: 连续的三个下划线
* `---`: 连续的三个破折号
* `***`: 连续的三个星号


演示:

___

---

***


## 影音

### 优酷视频嵌入

<iframe width="560" height="315" src="http://player.youku.com/embed/XMTQ1NzQ2ODgzNg==" frameborder="0" allowfullscreen></iframe>

### 图片

![外链图片](https://licensebuttons.net/l/by-nc-sa/2.5/cn/88x31.png)


你也可以使用HTML元素来调整图片的显示大小和位置等信息并可以通过点击图片的方式用lightbox显示缩放图片。

```<div class="row">
<p style="float: left; font-size: 9pt; margin-right:1em;"> 
   <a href="{{ site.baseurl }}/assets/images/icons/weibo.png" data-lightbox="gallery1" data-title="The first image" style="float: left; margin-left: 10%; margin-bottom: 1em;">
   <img src="{{ site.baseurl }}/assets/images/icons/weibo.png">Image#weibo</a>
   <a href="{{ site.baseurl }}/assets/images/icons/instagram.png" data-lightbox="gallery1" data-title="The first image" style="float: left; margin-right: -10%; margin-bottom: 1em;">
   <img src="{{ site.baseurl }}/assets/images/icons/instagram.png">Image#instagram</a></p>
</div>```


***




[^1]: 脚注1的注解 。

[^2]: 脚注2的注解及链接文档 - [点击这里查看链接！](#)

---
layout: post
title: "Markdown 语法备注"
date: 2013-02-27 16:50
comments: true
categories: [Octopress]
---

**备注**：具体样式需要修改screen.css

## Code and Syntax Highlighting
> Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and Markdown Here -- support syntax highlighting. 

##代码段示例之一：

{% highlight python %}
def yourfunction():
	   print "Hello World!"
{% endhighlight %}


##代码段示例1：

	def openFile(filepath){
		return File.open(filepath);
	}


### 无序列表
*   Red
	*   Red 1
	*   Red 2
*   Green
*   Blue


### 有序列表
1.  Bird
	1.  Ordered sub-list
	2.  Ordered sub-list
2.  McHale
	1. Ordered sub-list
3.  Parish
	1. Ordered sub-list

这是外部链接：[google](http://www.googlestable.com)

这是内部链接：[关于](/about/)

*斜体字*

**强调**


行内代码段：``There is a literal backtick (`) here.`` 结束

Use the `printf()` function.

![图片示例](/images/samples/octopress.png 'Octopress')


分行线
--------

 
## 表格 ##
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |---------------| ------|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |



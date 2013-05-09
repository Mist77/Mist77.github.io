---
layout: post
title: "如何将本地的文章上传到jekyll "
description: "如何将本地的文章上传到jekyll "
category: note
tags: [github]
---
{% include JB/setup %}

###
	1.输入命令~~~rake post~~新建一个YYYY-MM-DD-new-post.md的文件
	2.可以使用notepad++修改，标题内容等文字
	3.保存文件后，可按照下面代码：
Code
-----

	git add .
	git commit -m "my first commit"
	git push -u origin master

	完成之后你的代码就已经上传到博客上。
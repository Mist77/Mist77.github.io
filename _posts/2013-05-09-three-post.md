---
layout: post
title: "如何提交代码到github上"
description: "如何提交代码到github上"
category: note
tags: [github]
---
{% include JB/setup %}

创建本地库：mkdir my_homework
初始化本地库：git init
也可以在本地D盘建项目文件名homework，创建一个name.md文件，输入文章（防止乱码情况，最好使用Notepad++打开，格式为utf-8无bom格式）：
然后在cmd控制台，进入文件所在路径地址，输入以下命令.

    1.git add .
    2.git commit -m "my first commit"
    3.git push -u origin master
    
即可提交到github上.另 git add .是提交项目下的所有文件，若提交特定文件，命令可写为git add ./name.md。

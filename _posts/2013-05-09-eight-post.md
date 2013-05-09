---
layout: post
title: "git常用命令"
description: "git常用命令"
category: note
tags: [git]
---
{% include JB/setup %}

-git add .  (添加当前目录下的所有文件和子目录)
-git help  (获取git基本命令)
-git commit (提交当前工作目录的修改内容)
 git commit –-amend –m “message” （在一个commit id上不断修改提交的内容）
-git clone (取出服务器的仓库的代码到本地建立的目录中，与服务器交互）
-git push (将本地commit的代码更新到远程版本库中，例如 “git push origin”就会将本地的代码更新到名为orgin的远程版本库中)
-git pull origion master:branch2（将远程库中的master分支拷贝到本地的branch2分支上并进行合并，如果合并的时候发生冲突要自行进行解决）
-git remote add origin（添加远程版本库）
-git remote rm origin （删除远程版本库）
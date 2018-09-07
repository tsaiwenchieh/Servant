---
title: Git With VS Code
date: 2018-08-19 22:29:54
tags: VS Code
---

## Visual Studio Code使用Git版本控管



<!--more-->

### 初使化儲存庫(init)

![1](p1.png)

>`> git init`

### 暫存/捨棄變更(add)

![2](p4.png)

>`> git status`  
>`> git add --all`  
> `or`  
>`> git add .`

### 提交(commit)

![1](p2.png)

>`> git commit -m "First commit"`  
>`> git add status`

### 推送(push)

![1](p3.png)

>`> git remote add origin http://github`  
>`> git remote -v`  
>`> git push -u origin master`
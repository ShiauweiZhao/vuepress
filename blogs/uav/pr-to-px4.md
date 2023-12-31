---
title: "如何向PX4提交一个PR"
tags: 
 - PX4
 - git
date: 2020/05/29
---
# 前置知识 
由于PX4-Autopilot项目托管在Github，所以我们需要一些前置知识。
## git
git的具体使用可以看廖雪峰等相关文档，了解ssh 免密登录也是有必要的，这个网上相关文档很多。

对于我们想提一个pr，掌握以下几个命令就可以了 

    git clone  # 从远程仓库克隆代码
    git checkout -b  # 创建分支
    git add  # 将修改添加到暂存区 
    git commit # 将暂存区的代码 变成一个新提交的版本 
    git push # 向远程仓库推送代码 

## github

github这里 你需要注册一个github账号，然后去fork PX4-Autopilot的项目，fork项目后，在自己名下就可以看到一个PX4-Autopilot的项目了，使用https或者ssh的方式，用git将这个项目clone到本地。
# 代码修改 
使用```git checkout -b``` 创建分支,分支名建议叫做pr-xxxx添加自己的修改内容,使用```git status```查看修改内容，随后使用 ``` git add git commit git push```指令将分支推送到远端仓库。
# 提交pr
打开自己fork的PX4仓库 
![1](https://github.com/ShiauweiZhao/shiauweizhao.github.io/raw/master/images/pr-2-px4.jpg)
点击 compare & pull request 创建自己的pr，内容和标题应该尽可能表明具体功能，必要时可以上传视频，日志等。
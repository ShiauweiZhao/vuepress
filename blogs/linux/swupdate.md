---
title: "swupdate 升级方案"
tags: 
 - linux
 - swupdate
 - bsp
date: 2022/03/29
---

# swupdate简介
swupdate 一个 Linux 更新代理，旨在提供一种有效且安全的方式来现场更新嵌入式 Linux 系统。SWUpdate 支持本地和 OTA 更新，多种更新策略，并且在设计时考虑了安全性。,和他类似的有[RAUC](https://rauc.io/),[Mender](https://mender.io/).

# 为什么我选了swupdate
1.swupdate 支持buildroot,yocto(只支持 single-copy)等集成.

2.swupdate 完全免费,Mender有一些收费的选项.


# swupdate依赖 
    uboot  (version >2016.5)
    buildroot(version > 2019.x ?) 

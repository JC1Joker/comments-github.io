---
layout: post
title: Conda
date: 2019-01-01 00:00:00 +0800
category: tutorial
thumbnail: /style/image/logo.png
icon: book
---

* Contents 
Win常用conda命令
{:toc}


# Win常用conda命令

[toc]

## 查看当前环境下安装的工具

> pip list

或

> conda list



## 创建虚拟环境

> conda create --name[环境名称]

例

> conda create --name hacker

即可创建一个名为hacker的虚拟环境

## 查看当前虚拟环境

> conda env list

其中带有*** **的表示当前所用的环境

## 切换环境

使用activate(激活)加上要切换的环境名称，即可切换

> activate[环境名称]

例

> activate learn 



## 退出虚拟环境

> conda deactivate



## 移除虚拟环境

> conda remove --name [环境] --all

例

> conda remove --name learn --all



## 包的安装

（无需进入环境）

> conda install [包名] -n [环境名]

## 包的删除

> conda remove [包名]












---
date: 2014-03-21 23:00:00+00:00
layout: post
title:  '[Python 标准库] 第十七章 运行时特性'
categories: 读书笔记
tags: Python
---

#### 第十七章 运行时特性

##### 17.1 site - 全站点配置
作用：site 模块处理站点的配置，特别是导入路径  

##### 17.2 sys - 系统特定的配置
作用：提供系统特定的配置和操作  

##### 17.3 os - 可移植访问操作系统特定特性
作用：可一直访问操作系统特定特性  

##### 17.4 platform - 系统版本信息
作用：探查底层平台的硬件、操作系统和解释器版本信息  

##### 17.5 resource - 系统资源管理
作用：管理 UNIX 程序的系统资源限制  
**函数**  
`getrusage()`：查看当前进程和其子进程使用的资源  

##### 17.6 gc - 垃圾回收器
作用：管理 Python 对象使用的内存  

##### 17.7 sysconfig - 解释器编译时配置
作用：访问用于构建 Python 的配置设置  
**函数**  
`get_config_vars()`：获取配置  
`get_platform()`：获取平台信息  

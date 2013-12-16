---
date: 2013-12-16 14:47:20+00:00
layout: post
title: 配置 Django 开发环境
categories: 编程
tags: Python Django
---

系统：window 7  

##### 1. 安装 Django
假设下载的Django在目录c:\Django下。在Django目录中有个`setup.py`,打开'cmd.exe'输入'python c:\Django\setup.py install',然后等待自动安装。  

##### 2. 配置系统环境
假设 Python 安装在`c:\Python27`, Django 就安装在`c:\Python27\Lib\site-packages\django\bin`。将其添加到`path`中。  

##### 3.测试 Django 是否安装成功
打开 IDLE，输入`import django`，如果没有报错，Django 安装成功。

参考：[Windows下安装Django及WEB服务启动](http://www.cnblogs.com/zhoujie/archive/2013/05/11/django1.html)
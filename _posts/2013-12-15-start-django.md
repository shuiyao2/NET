---
data: 2013-12-15 22:40:12+00:00
layout: post
title: Django 入门
categories: 编程
tags: Python Django
---

注意相关路径，全部是在 `cmd.exe` 中操作。

#### 1. 创建 Django 工程
找到文件`django-admin.py`所在的目录，然后输入`python django-admin.py -h`，查看相关命令。如`python django-admin.py startproject {project_name}`创建工程。

#### 2. 启动服务器
在工程中找到文件`manage.py`所在目录，然后输入`manage.py -h`，查看相关命令。如`manage.py runserver [[ip:]端口]`启动服务器。

#### 3. 输入 url 访问
根据服务器的相关信息，如`http://local:端口/[函数名]` 或者 `http://127.0.0.1:端口/[函数名]`。

#### 4. 其他命令
Django中的应用是以`app`形式存在，如安装 app 的命令是：`manage.py startapp {app_name}`；  
后台 Admin 创建超级用户的命令是：`manage.py createsuperuser {username}`；  
创建表的命令是：`manage.py syncdb`，可以多吃运行，不会重复创建表；  
在 Django 工程中使用 shell 的命令是：`manage.py shell`;  

参考：[Django入门实践（一）](http://www.cnblogs.com/zhoujie/p/django2.html)  
更多内容: Django 入门教程：[中文版](http://read.douban.com/ebook/284513/)|[英文版](https://docs.djangoproject.com/en/1.5/intro/tutorial01/)
---
date: 2014-03-16 23:00:00+00:00
layout: post
title:  '[Python 标准库] 第十章 进程与线程'
categories: 读书笔记
tags: Python
---

#### 第十章 进程与线程

##### 10.1 subprocess - 创建附加进程
作用：创建附加进程，并与之通信  
**函数**  
`call()`：运行一个外部命令  
`check_call()`：检查退出码  
`check_output()`：捕获命令的输出 
`communicate()`：读取所有输出  

##### 10.2 signal - 异步系统事件
作用：发送和接受异步系统事件  
**函数**  
`getsignal()`：获取已注册的处理程序  

##### 10.3 theading - 管理并发操作
作用：建立在 thead 模块之上，管理多个执行线程  
**函数**  
`start()`：线程开始  
`wait()`：等待线程  

##### 10.4 multiprocessing - 像线程一样管理进程
作用：提供一个 API 来管理进程  
**函数**  
`Process()`：实例化一个 Process 对象  
`start()`：开始运行  
`get_logger()`：处理日志记录器  

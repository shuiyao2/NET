---
date: 2014-03-17 23:00:00+00:00
layout: post
title:  '[Python 标准库] 第十一章 网络通信'
categories: 读书笔记
tags: Python
---

#### 第十一章 网络通信

##### 11.1 socket - 网络通信
作用：提供对网络通信的访问  

11.1.1 寻址、协议簇和套接字类型  
**函数**  
`gethostname()`：访问操作系统主机名  
`gethostbyname()`：访问操作系统主机数字地址  
`gethostbyname_ex()`：访问操作系统主机名、别名和所有可用 IP 地址  
`getfqdn()`：将一个部分名转换为完全限定域名  
`gethostbyaddr()`：由 IP 地址操作主机名  
`getservbyname()`：服务器端口和标准名  
`getservbyport()`：由端口查找服务器名  
`getprotobyname()`：获取分配给一个传输协议的端口号  
`getaddrinfo()`：获取一个服务的基本地址，返回一个*元组*列表  

11.1.2 TCP/IP 客户和服务器  
**函数**  
`bind()`：将套接字与服务器地址关联  
`listen()`：将套接字置为服务器模式  
`accept()`：返回服务器与客户之间一个打开的连接，并返回客户地址  
`close()`：关闭连接  
`sendall()`：发送数据  
`recv()`：接受数据  
`create_connection()`：连接服务器  
`getsockname()`：获取套接字的具体地址  

11.1.3 用户数据报客户和服务器  
**函数**  
`bind()`：将套接字与端口关联  
`recvfrom()`：从套接字读取信息  
`sendto()`：将消息传送到服务器  

##### 11.2 select - 高效等待 I/O
作用：等待输入或输出通道已经准备就绪的通知  

##### 11.3 SocketServer - 创建网络服务器
作用：创建网络服务器  

##### 11.4 asyncore - 异步 I/O
作用：异步 I/O 处理器  

##### 11.5 asynchat - 异步协议处理器
作用：异步网络通信协议处理器  

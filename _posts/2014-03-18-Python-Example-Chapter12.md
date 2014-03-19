---
date: 2014-03-18 10:00:00+00:00
layout: post
title:  '[Python 标准库] 第十二章 Internet'
categories: 读书笔记
tags: Python
---

#### 第十二章 Internet

##### 12.1 urlparse - 分解 URL 
作用：将 URL 分解为其组成部分  

##### 12.2 BaseHTTPServer - 实现 Web 服务器的基类
作用：BaseHTTPServer 包含一些类，可以构成 Web 服务器的基础  

##### 12.3 urllib - 网络资源访问
作用：访问不需要验证的远程资源、cookie 等等  
**函数**  
`urlretrieve()`：使用一个 HTTP GET 请求从一个 Web 服务器获取数据  
`urlencode()`：将参数编码并追加到 URL  

##### 12.4 urllib2 - 网络资源访问
作用：用于打开扩展 URL 的库，URL 可以通过定义定制协议处理来扩展  
**函数**  
`urlopen()`：打开链接  
`urlencode()`：对参数编码并追加到 URL，将参数传递到服务器  
`add_data()`：提交请求参数  

##### 12.5 Base64 - 用 ASCII 编码二进制数据
作用：base64 模块包含一些函数，可以将二进制数据转换为合适使用纯文本协议传输的 ASCII 子集  

##### 12.6 robotparser - 网络蜘蛛访问控制
作用：解析用于控制网络蜘蛛的 robot.txt 文件  

##### 12.7 Cookie - HTTP Cookie
作用：Cookie 模块定义一些类来解析和创建 HTTP cookie 首部  
**函数**  
`SimpleCookie()`：创建 Cookie  

##### 12.8 uuid - 全局惟一标识符
作用：uuid 模块实现了全局惟一标识符  
**函数**  
`getnode()`：获取当前系统的 MAC 值  
`uuid1()`：为一个主机生成一个 UUID  

##### 12.9 json - Javascript 对象记法
作用：将 Python 对象编码为 JSON 串，以及将 JSON 串解码为 Python 对象  

##### 12.10 xmlrpclib - XML-RPC 的客户端库
作用：XML-RPC通信的客户端库  

###### 12.11 SimpleXMLRPCServer - 一个 XML-RPC 服务器 
作用：实现一个 XML-RPC  服务器  

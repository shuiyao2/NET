---
date: 2014-03-22 23:00:00+00:00
layout: post
title:  '[Python 标准库] 第十九章 模块与包'
categories: 读书笔记
tags: Python
---

#### 第十九章 模块与包

##### 19.1 imp - Python 的导入机制
作用：imp 模块提供了 Python import 语句的实现  
**函数**  
`find_module()`：查找模块  
`load_module()`：导入模块  

##### 19.2 zipimport - 从 ZIP 归档加载 Python 代码
作用：导入作为 ZIP 归档成员保存的 Python 模块  
**函数**  
`zipimporter()`：加载 ZIP 归档  
`find_module()`：在 ZIP 归档中查找模块  
`get_code()`：从 ZIP 归档中加载一个模块的代码对象  
`load_module()`：加载为一个可用的模块  
`is_package()`：检测是否为一个模块  

##### 19.3 pkgutil - 包工具
作用：增加到一个特定包的模块搜索路径，并处理包中包含的资源  


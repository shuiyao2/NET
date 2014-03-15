---
date: 2014-03-15 20:00:00+00:00
layout: post
title:  '[Python 标准库] 第七章 数据持久存储与交换'
categories: 读书笔记
tags: Python
---

#### 第七章 数据持久存储与交换

##### 7.1 pickle - 对象串行化
作用：对象串行化  
7.1.1 导入  
```python
try:
	import cPickle as pickle
except:
	import pickle

```

7.1.2 编码和解码字符串数据  
**函数**  
`dumps()`：编码字符串  
`load()`：解码字符串  

##### 7.2 shelve - 对象持久存储
作用：shelve 模块使用一种类字典的 API,可以持久存储可 pickle 的任意 Python 对象  
**函数**  
`open()`：访问 anydbm 存储数据  

##### 7.3 anydbm - DBM 数据库
作用：anydbm 为以字符串为键的 DBM 数据库提供了一个通用的类字典接口  

##### 7.4 whichdb - 识别 DBM 数据库格式
作用：检查现有的 DBM 数据库文件，以确定应当使用哪个库来打开该文件  

##### 7.5 sqlite3 - 嵌入式关系数据库
作用：实现一个嵌入式关系数据库，并提供 SQL 支持  

##### 7.6 xml.etree.ElementTree - XML 操纵 API
作用：生成和解析 XML文档  

##### 7.7 csv - 逗号分隔值文件
作用：读写逗号分隔文件  

**函数**  
`reader()`：创建一个对象从 CSV 文件读取数据  
`writerow()`：创建一个对象将数据写入 CSV 文件  

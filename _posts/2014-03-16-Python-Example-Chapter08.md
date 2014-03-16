---
date: 2014-03-16 17:00:00+00:00
layout: post
title:  '[Python 标准库] 第八章 数据压缩与归档'
categories: 读书笔记
tags: Python
---
#### 第八章 数据压缩与归档

##### 8.1 zlib - GNU zlib 压缩
作用：对 GNU zlib压缩库的底层访问  

**函数**  
`compress()`：压缩函数，取一个字符串参数，并返回一个字符串  
`decompress()`：解压函数，取一个字符串参数，并返回一个字符串  

##### 8.2 gzip - 读写 GNU Zip 文件
作用：读写 gzip 文件  
**函数**  
`open()`：创建一个类文件的类  
`writelines()`：写入字符串序列  

##### 8.3 bz2 - bzip2 压缩
作用：完成 bzip2 压缩  
**函数**  
`BZ2Compressor()`：增量压缩  
`BZ2DeCompressor()`：解压缩  
`BZ2File()`：读写 bzip2 压缩文件  

##### 8.4 tarfile - Tar 归档访问
作用：读写 tar 归档文件  
**函数**  
`is_tarfile()`：返回一个*布尔值*，指示作为参数传入的文件名是否
指向一个合法的 tar 归档文件  
`getnames()`：读取一个现有归档文件中的文件名  
`getmember()`：获取 TarInfo 对象元数据  
`getmembers()`：获取 TarInfo 对象元数据  
`extractfile()`：访问一个归档成员的数据  
`extract()`、`extractall()`：将文件写入文件系统  
`add()`：添加文件  

##### 8.5 zipfile - ZIP 归档访问
作用：读写 ZIP 归档文件  
**函数**  
`is_zipfile()`：返回一个布尔值，指示作为参数传入的文件名是否指向一个合法的 ZIP 归档  
`namelist()`：返回一个现有归档中的文件名  
`infolist()`、`getinfo()`：访问有关 ZIP 内容的所有元数据  
`getinfo()`：获取 ZipInfo 对象  
`read()`：访问数据  

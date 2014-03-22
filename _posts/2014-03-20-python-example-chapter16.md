---
date: 2014-03-20 20:00:00+00:00
layout: post
title:  '[Python 标准库] 第十六章 开发工具'
categories: 读书笔记
tags: Python
---

#### 第十六章 开发工具

##### 16.1 pydoc - 模块的联机帮助
作用：从代码为 Python 模块和类生成帮助  

##### 16.2 doctest - 通过文档完成测试
作用：编写自动化测试，作为模块文档的一部分  

##### 16.3 unittest - 自动测试框架
作用：自动测试框架  
**函数**  
`setUp()`：配置函数  
`tearDown()`：清理函数  

##### 16.4 traceback - 异常和栈轨迹
作用：抽取、格式化和打印异常及栈轨迹  
**函数**  
`print_exc()`：处理异常报告  
`print_stack()`：打印当前栈  

##### 16.5 cgitb - 详细的 traceback 报告
作用：cgitb 能提供比 traceback 更为详细的 traceback 信息  

##### 16.6 pdb - 交互式调试工具
作用：Python 的交互式调试工具  

##### 16.7 trace - 执行程序流
作用：监视程序运行时执行的语句和函数，生成覆盖和调用图信息  

##### 16.8 profile 和 pstats - 性能分析
作用：Python 程序的性能分析  

##### 16.9 timeit - 测量小段 Python 代码的执行时间
作用：测量小段 Python 代码的执行时间  

##### 16.10 compileall - 字节编译源文件
作用：将源文件转换为字节编译版本  
**函数**  
`compile_dir()`：将目录中的文件编译成字节  
`compile_path()`：编译 sys.path 中找到的所有 Python 源文件  

##### 16.11 pyclbr - 类浏览器
作用：实现一个适用于源码编辑器的 API，建立一个类浏览器  

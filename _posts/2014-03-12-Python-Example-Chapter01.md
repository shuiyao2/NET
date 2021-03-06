---
date: 2014-03-11 15:08:00+00:00
layout: post
title: '[Python 标准库] 第一章 文本'
categories: 读书笔记
tags: Python 
---

#### Chapter01 文本

##### 1.1 string - 文本常量和模板
作用：包含处理文本的常量和类。  
1.1.1 函数  
`capwords(s)`：字符串中所有单词首字母大写  
`maketrans()`：创建转换表  
`translate()`:将一组字符修改为另外一组字符  

1.1.2 模板  
使用string.Template拼接时，可以在变量前加前缀 $ (如 $var )来标示变量，
或者如果需要与两侧的文本相区分可以使用大括号将变量括起来(如 ${var} )。  
通过使用saft_substitute()方法避免未能提供模板所需全部参数时产生的异常。  

1.1.3 高级模板
修改string.Template默认语法，调整其在模板体重查找变量名所使用的正则表达式。
1,修改 delimiter 和 idpattern 类属性。2,覆盖 pattern 属性，定义一个全新的正则表达式。  


##### 1.2 textwrap - 格式化文本段落
作用：通过调整换行符在段落中出现的位置来格式化文本。  
1.2.1 函数  
`fill()`：函数取文本作为输入，生成格式化的文本作为输错。  
`dedent()`：去除缩进(每行最前面的空白符)  
`indent()`：缩进  


##### 1.3 re - 正则表达式
作用：使用形式化模式搜索和修改文本。  
1.3.1 函数  
`search()`：搜索文本  
`compile()`：将表达式字符串转换为一个 RegexObject  
`findall()`：返回与模式匹配而不重叠的所有子串  
`finditer()`：返回一个迭代器  

1.3.2 转义码  
1.3.3 锚定  
1.3.4 缩写  


##### 1.4 difflib - 比较序列
作用：比较序列  
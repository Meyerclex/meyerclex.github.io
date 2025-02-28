---
title: "Scope 作用域"
tags: 
- JavaScript
---


## Scope 作用域

![](https://raw.githubusercontent.com/Meyerclex/image/main/20220821165520.png)
- JS作用域：变量在某个范围内起作用和效果，目的是为了提高程序的可靠性，减少命名冲突。
	1. 全局作用域：整个`<script>`标签，或者是一个单独的JS文件。
	2. 局部作用域：在函数内部就是局部作用域，只在函数内部其效果和作用。
- 变量作用域
	- 全局变量：全局作用域下的变量。如果在函数内部没有声明直接赋值的变量也属于全局变量。
	- 局部变量：在局部作用域下的变量，只能在函数内部使用。函数的形参也可以看作是局部变量
- 从执行效率来看变量作用域
	- 全局变量只有浏览器关闭时才销毁，占内存资源
	- 局部变量当程序执行完毕就会销毁，节约内存资源
- [[Block area 块作用域]]

## Scope chain 作用域链
- 根据内部函数可以访问外部函数变量的这种机制，用链式查找决定哪些数据能被内部函数访问，就成为作用域链。
- ![](https://raw.githubusercontent.com/Meyerclex/image/main/20220907110924.png)
- ![](https://raw.githubusercontent.com/Meyerclex/image/main/20220907111027.png)

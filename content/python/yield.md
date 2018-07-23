---
title: "yield"
date: 2018-07-23T16:26:03+08:00
draft: false
---
- 带有yield 的函数是一个生成器generator，用于迭代
- yield 类似于return 的关键字，迭代一次就返回yield 后面的值，下一次迭代就从上一
次迭代遇到的yield 后面的代码开始执行
- yield 就是return 返回一个值并记住该值的位置，下次迭代就从这个位置后开始
- 调用yield 函数，内部代码不马上执行，只是返回一个生成器对象，使用for进行迭代时
，函数中的代码才会执行

---
- 判断一个函数是否为generator函数：
- from inspect import isgeneratorfunction
- isgeneratorfunction(function_name)
---

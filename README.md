> # My-daily-summary
# day01. 2021.05.08学习记录
### 1. 前端学习
1. 算法题1道 hash表相关的，判断一个字符串是否可以用另外一个字符串里面的字符组成。当遇到需要快速查找或者大量查找的问题考虑使用Hash表，然后字母总共就26个通常可以通过数组+数组下标来实现hash表。用`s.charCodeAt(i)-'a'.charCodeAt(1)`来确定下标。
2. `Array.prototype.forEach`方法的实现，主要是`this`的改变，使用`call`函数可以改变参数(函数)的this指向。写这种函数都需要首先判断传进来的参数是否符合要求，比如`callback`是否是回调函数，总共穿了几个参数`arguments.length`长度判断。
3. `Array.prototype.reduce`方法实现，需要判断是否传入了初始值，没有传入就是用数组第一个值，数组长度也要判断，为0就直接返回。
4. 贝壳找房前端实习笔试，总共四道题，两道70%；oj输入输出比之前要熟练很多了。
### 2. 论文进展
1. 论文：分析PCPF，CICPF原理。
2. 明天开始仿真实现CPF？
# day02. 2021.05.10学习记录（02）
### 1. 论文CPF仿真实现
- 确定CPF仿真实现的思路，如何实现。
- next`——>`阅读时频工具箱提供的tfrwv函数，参考编写信号CPF实现代码。

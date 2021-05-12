> # My-daily-summary
# day01. 2021.05.08学习记录
> ### 1. 前端学习
> 1. 算法题1道 hash表相关的，判断一个字符串是否可以用另外一个字符串里面的字符组成。当遇到需要快速查找或者大量查找的问题考虑使用Hash表，然后字母总共就26个通常可以通过数组+数组下标来实现hash表。用`s.charCodeAt(i)-'a'.charCodeAt(1)`来确定下标。
> 2. `Array.prototype.forEach`方法的实现，主要是`this`的改变，使用`call`函数可以改变参数(函数)的this指向。写这种函数都需要首先判断传进来的参数是否符合要求，比如`callback`是否是回调函数，总共穿了几个参数`arguments.length`长度判断。
> 3. `Array.prototype.reduce`方法实现，需要判断是否传入了初始值，没有传入就是用数组第一个值，数组长度也要判断，为0就直接返回。
> 4. 贝壳找房前端实习笔试，总共四道题，两道70%；oj输入输出比之前要熟练很多了。
> ### 2. 论文进展
> 1. 论文：分析PCPF，CICPF原理。
> 2. 明天开始仿真实现CPF？

# day02. 2021.05.10学习记录
> ### 1. 论文CPF仿真实现
> - 确定CPF仿真实现的思路，如何实现。
> - next`——>`阅读时频工具箱提供的tfrwv函数，参考编写信号CPF实现代码。

# DAY03. 2021.05.11学习记录
> ### 1. 前端学习
> 1. 算法题：三数之和 四数之和都用双指针解决 `nums[i]+nums[j]+nums[left]+nums[right]`，字符串相关专题，字符串数组的反转，字符串间隔2k个反转前k个。
> 2. TypeScript学习，为什么会有TypeScript,TypeScript相比JS有什么区别，JS太灵活，比如变量没有类型，可以赋值数字类型也可以赋值字符串类型，这样在有的代码中会有问题但是JS又不会报错，我的初步理解是TypeScript是需要受一定约束的JS。
> 
> ```js
> a=12;
> a='str';
> ```
> ### 2. 论文进展
> 1. WVD仿真实现。对横坐标，纵坐标的理解，以及对应实际值。[参考](https://blog.csdn.net/qq_38294099/article/details/116611166)
# DAY04 2021.05.12
> ### 1. 前端学习
> 1. 算法题：替换字符串里面的空格，可以先对数组扩充然后使用双指针把原来的往后移动，遇到空格替换；翻转字符里面的单词；
> 2. 听了一个小时的公开直播课；
> 3. TypeScript学习，搭建ts坏境，.ts文件需要编译为.js文件浏览器才能识别；TypeScript种变量的类型，有一些我们熟悉的也有一些之前没有接触过的，为变量定义指定类型，也可以为函数参数 函数返回值指定类型；注意区分any 和unknown类型；
> ### 2. 论文仿真
> 1. 实现WVD代码，但是还未弄清楚实现原理以及对应的CPF代码思路。

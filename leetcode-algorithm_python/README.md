# leetcode分类高效刷题


leetcode是一个很好的学习算法的一个online judge的网站，通过刷题能够快速提升自己的算法能力。但是令大家都头疼的就是，怎么能够高效的通过leetcode刷题掌握算法的做题技巧，并且顺利通过面试。

**刷题的时候千万不要怀疑自己的智商，不要怀疑自己的智商，不要怀疑自己的智商**

每个人都要经历从无到有的过程，刚开始都是不会（大佬请自动忽略），一度怀疑自己的智商。刚开始做题，一度怀疑自己是不是不适合编程，硬着头皮做下去，分类刷完这些类别之后，再拿到题目时，自己有了一些思路，困难的题目虽然还是做不出来，但是已经有了思路，发现很多也没那么难。

小伙伴们加油一起熬过这段苦逼的时光，坚持下来，一段时间之后会发现自己已经有了很大长进了，相信等你刷完这个仓库中分类的200多道题，回头看发现自己已经之前厉害了好多。

leetcode刷题一方面为后期的面试做准备，同时也用于学习一定的算法基础，通过刷题实训来提高自己的工程能力，
本项目的代码实现均采用python实现，但是不采用python库中的函数，基本上采用算法思想实现，所以具体的语言
并不重要，但是对于其他的语言可能要考虑越界与数据类型转换的问题

本仓库记录自己的做题过程，分类别整理一部分基础并且经典的习题，分类别刷题有助于算法思想的培养。

## 分类整理项目介绍
将算法题目分门别类的进行整理，将一个题目相关的类型多做几道，熟练算法思想

分类别进行刷题，是一个非常高效的方法，但是直接使用leetcode的类别标签做题，很难从中找到代表性的题目，自己很难通过这些题目总结自己的一个算法做题的框架，对于算法的思路整理熟练并不十分有用，本项目就是记录自己的刷题leetcode过程中，根据网络上的资料及自己看的算法课程，总结了在leetcode上每个类别的代表性的题目，

每个类别整理记录相应的代表性题目，每一类大概整理10几道题目，相信通过做这些题目，一定会对这一类的算法能有很好的理解，并且对这一类的题目会有思路。每类题目开始的几道题，会有比较详python细的代码注释，后边的题目解法，大体的解题框架与思路比较一致，就只给出相对应的python代码实现，所有的代码均accept，有些题目的解法在leetcode上的效率并不高，但是对于初始刷题做题的解法思路还是比较有帮助，在相应的基础解决思路上进行优化更有利用算法思想的培养建立。

目前我也正在学习中，分类整理大概各种leetcode算法题目前大概整理230道左右，在刷题过程中持续更新。

对于很多题目，我都整理自己能够想到的对于思路培养有用的几种解法，有些题目的解题思路都是从暴力法，然后一步步优化然后想到相对好一点的解法。

请大家记住很有用的一句话：**暴力法是思路的起点**

对于一道题目，如果没有思路想想怎么采用暴力法进行求解，可能大多数情况下，这种解法在leetcode上会超时，但是根据对应的暴力法解法，
然后进行时间空间复杂度的优化，也是一个很好的策略。

目前我所做的这些题，常用的暴力法及优化策略就是：

* 多层循环 ——> 利用hashmap，空间换时间
* 递归回溯 ——> 剪枝，或者对于重叠子问题用dp（动态规划）

```
|-- 双指针
    |-- 双指针（对撞指针）
    |-- 双指针(快慢指针)
    |-- 其他双指针
|-- 哈希表
    |-- 哈希表
|-- 排序
    |-- 排序
|-- 二分查找
    |-- 二分查找
|-- 数组与矩阵
    |-- 数组与矩阵
|-- 链表
    |-- 链表
|-- 栈与队列
    |-- 栈与队列
|-- 树与递归
    |-- 递归
    |-- 遍历
    |-- 二叉搜索树
    |-- 回溯
|-- 贪心算法
    |-- 贪心算法
|-- 分治法
    |-- 分治法
|-- 动态规划
    |-- 动态规划
    |-- 背包问题
|-- 搜索
    |-- 搜索
|-- 图
    |-- 图
|-- 位运算
    |-- 位运算
|-- 每日一题
    |-- 每日一题
```

相信刷完这200多道题，再做题的时候思路就比较明了了。

##  每日一题

leetcode刷题需要长期坚持，当按类别算法知识基本学习之后，就每天刷一道题，持续更新，部分内容参考：[Leetcode 题解](CyC2018/CS-Notes)

放上github地址，整理不易，欢迎star。
github地址：[https://github.com/lxztju/leetcode-algorithm](https://github.com/lxztju/leetcode-algorithm)
# 计算机视觉算法工程师面试中手撕代码的算法题总结

## 希望大家把自己的面试题目加进来，一起维护！本人本科非科班，可能一些划分和解答不合理，欢迎指出！

## （目前是微软、商汤、旷视、头条、阿里、腾讯、百度、海康威视、第四范式算法岗，其他公司也可以添加。）

## 1.按照公司划分

### 微软
1.n个文件（海量文件），查找和排序，二分查找时间复杂度（**微软**）

归并排序，二分查找

2.算法：一个数组里面是股票值，求什么时候购买和卖出，收益最大。

其实就是给定一个数组A，求max(Ai - Aj)。其中 i >j 。

一个数记录最大差，一个记录最小元素，遍历一次即可

[leetcode 121](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)

[leetcode 122]

[leetcode 123]

[leetcode 188]

[leetcode 309]

3.最长连续公共子串（**微软**）

### 商汤
1.二叉树路径和为某一值的路径（**商汤**）

[剑指offer 24](https://www.nowcoder.com/practice/b736e784e3e34731af99065031301bca?tpId=13&tqId=11177&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)

2.数组中只出现一次的数字（**商汤**）

[剑指offer 40](https://www.nowcoder.com/practice/e02fdb54d7524710a7d664d082bb7811?tpId=13&tqId=11193&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)

3.链表中倒数第k个结点（**商汤**）

[剑指offer 14](https://www.nowcoder.com/practice/529d3ae5a407492994ad2a246518148a?tpId=13&tqId=11167&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)

### 旷视
1.数组中的逆序对（**旷视**）

[剑指offer 35](https://www.nowcoder.com/practice/96bd6684e04a44eb80e6a68efc0ec6c5?tpId=13&tqId=11188&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)

### 今日头条

1.x的n次方

[leetcode 50](https://leetcode.com/problems/powx-n/)

2.链表排序（**头条**）

[leetcode 148](https://leetcode.com/problems/sort-list/)

3.螺旋打印二维数组（**头条**）

[leetcode 54](https://leetcode.com/problems/spiral-matrix/)

4.扎气球（**头条**）

[leetcode 452](https://blog.csdn.net/yysave/article/details/84403875)

5.链表反转（**头条**）

[剑指offer 15](https://www.nowcoder.com/practice/75e878df47f24fdc9dc3e400ec6058ca?tpId=13&tqId=11168&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)


### 阿里巴巴

### 腾讯

### 百度

### 海康威视
1.二叉树的深度（**海康**）

[剑指offer 38](https://www.nowcoder.com/practice/435fb86331474282a3499955f0a41e8b?tpId=13&tqId=11191&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)

2.排序（**海康**）

快排，归并，堆排序

3.跳台阶（**海康**）

[剑指offer 8](https://www.nowcoder.com/practice/8c82a5b80378478f9484d87d1c5f12a4?tpId=13&tqId=11161&tPage=1&rp=1&ru=%2Fta%2Fcoding-interviews&qru=%2Fta%2Fcoding-interviews%2Fquestion-ranking)

4.连续子数组的最大和（**海康**）

[剑指offer 30](https://www.nowcoder.com/practice/459bd355da1549fa8a49e350bf3df484?tpId=13&tqId=11183&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)

5.最长不重复子串（**海康**）

[leetcode 3/剑指offer第二版48](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

### 第四范式

1.删除字符(**第四范式**)
```
abcdabcd 4
bcdabcd
bcdbcd
cdbcd
cdcd
```
2.螺旋三角形输出(**第四范式**)
```
5

1
2 12
3 13 11
4 14 15 10
5 6  7  8  9
```

### 同学or面经题目（other）

1.判断链表对称/链表回文

2.求一个数组中只包含0,1使得其中0,1个数相等的最大子数组（百度）

3.给定一个二叉树pNode* root，找到二叉树里的pNode* target节点，并打印出路径（**阿里**）

先序遍历，一个vector存路径递归即可

[参考解答](https://blog.csdn.net/shixiaoguo90/article/details/23759887)

4.最长公共子序列（阿里）

## 数据结构类
### 1.链表
商汤-3
头条-2，5
### 2.数组
### 3.字符串
### 4.栈与队列
### 5.二叉树
商汤-1
海康-1
other-3
### 6.二叉搜索树
### 7.数组计数
第四范式-1
### 7.哈希表
## 算法类
### 1.递归
海康-3
### 2.排序
微软-1
旷视-1
海康-2
### 3.搜索
### 4.回溯
### 5.位运算
商汤-2
### 6.动态规划
微软-3
海康-4
海康-5
### 7.双指针
### 8.贪心
头条-4
### 9.限制运算
### 10.找规律
头条-3
第四范式-2 


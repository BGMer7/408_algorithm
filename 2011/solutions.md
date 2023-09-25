### 方法一：合并数组

合并、排序、找到中位数，是最简单的一种方法。

加上条件给出“两个等长序列”、“长度大于等于1”。难度较小，应该可以无伤速通。



- 时间复杂度O(n)

- 空间复杂度O(n)

个人评分：7分，主体思路正确，但时间复杂度和空间复杂度都有较大优化空间。



优化思路：辅助数组只需要一个变量用于保存合并了n个元素的最后一个，最后直接返回。

- 时间复杂度O(n)

- 空间复杂度O(1)


个人评分：8分，主体思路正确，但时间复杂度有较大优化空间。





### 方法二：基于值域的二分查找

基于值域的二分查找是找第K小的元素的固定模板，详见千叶原力扣原创题解[多重二分查找 + 多维度二分查找](https://link.zhihu.com/?target=https%3A//leetcode.cn/problems/median-of-two-sorted-arrays/solution/by-sui-xin-yuan-f9an/)。
### 二分法查找
- 易错重难点
```
1.while(left < right ) /还是left <= right？
2.if(num[middle] > target)
  right = middle /还是middle-1？
3.在二分法中，一般都是[left, right](左闭右闭合)；[left, right)(左闭右开)；
（left, right](左闭右开这种情况很少)
```
题目：[binary search](https://leetcode.cn/problems/binary-search/)

### 数组删除
- 易错重难点

1.数组无法删除，只能覆盖；覆盖之后的数组空间不变，但是size会根据删减发生变化，c中使用vector的erase，其他的语言也是提供类似的接口

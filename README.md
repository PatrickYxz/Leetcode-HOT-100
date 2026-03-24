# LeetCode HOT 100

> 记录刷题过程中的思路与收获，持续更新中。

**进度：** 7 / 100

---

## 目录

- [哈希](#哈希)
- [双指针](#双指针)
- [滑动窗口](#滑动窗口)
- [子串](#子串)
- [普通数组](#普通数组)
- [矩阵](#矩阵)
- [链表](#链表)
- [二叉树](#二叉树)
- [图论](#图论)
- [回溯](#回溯)
- [二分查找](#二分查找)
- [栈](#栈)
- [堆](#堆)
- [贪心](#贪心)
- [动态规划](#动态规划)

---

## 哈希

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 1 | [两数之和](https://leetcode.cn/problems/two-sum/) | 🟢 简单 | - | - |
| 49 | [字母异位词分组](https://leetcode.cn/problems/group-anagrams/) | 🟡 中等 | - | - |
| 128 | [最长连续序列](https://leetcode.cn/problems/longest-consecutive-sequence/) | 🟡 中等 | - | - |

---

## 双指针

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 11 | [盛最多水的容器](https://leetcode.cn/problems/container-with-most-water/) | 🟡 中等 | - | - |
| 15 | [三数之和](https://leetcode.cn/problems/3sum/) | 🟡 中等 | - | - |
| 42 | [接雨水](https://leetcode.cn/problems/trapping-rain-water/) | 🔴 困难 | - | - |
| 283 | [移零](https://leetcode.cn/problems/move-zeroes/) | 🟢 简单 | - | - |

---

## 滑动窗口

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 3 | [无重复字符的最长子串](https://leetcode.cn/problems/longest-substring-without-repeating-characters/) | 🟡 中等 | - | - |
| 438 | [找到字符串中所有字母异位词](https://leetcode.cn/problems/find-all-anagrams-in-a-string/) | 🟡 中等 | - | - |

---

## 子串

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 76 | [最小覆盖子串](https://leetcode.cn/problems/minimum-window-substring/) | 🔴 困难 | - | - |
| 239 | [滑动窗口最大值](https://leetcode.cn/problems/sliding-window-maximum/) | 🔴 困难 | - | - |
| 560 | [和为 K 的子数组](https://leetcode.cn/problems/subarray-sum-equals-k/) | 🟡 中等 | - | - |

---

## 普通数组

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 31 | [下一个排列](https://leetcode.cn/problems/next-permutation/) | 🟡 中等 | - | - |
| 41 | [缺失的第一个正数](https://leetcode.cn/problems/first-missing-positive/) | 🔴 困难 | - | - |
| 53 | [最大子数组和](https://leetcode.cn/problems/maximum-subarray/) | 🟡 中等 | - | - |
| 56 | [合并区间](https://leetcode.cn/problems/merge-intervals/) | 🟡 中等 | - | - |
| 189 | [轮转数组](https://leetcode.cn/problems/rotate-array/) | 🟡 中等 | - | - |
| 238 | [除自身以外数组的乘积](https://leetcode.cn/problems/product-of-array-except-self/) | 🟡 中等 | - | - |

---

## 矩阵

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 48 | [旋转图像](https://leetcode.cn/problems/rotate-image/) | 🟡 中等 | - | - |
| 54 | [螺旋矩阵](https://leetcode.cn/problems/spiral-matrix/) | 🟡 中等 | - | - |
| 73 | [矩阵置零](https://leetcode.cn/problems/set-matrix-zeroes/) | 🟡 中等 | - | - |
| 240 | [搜索二维矩阵 II](https://leetcode.cn/problems/search-a-2d-matrix-ii/) | 🟡 中等 | - | - |

---

## 链表

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 2 | [两数相加](https://leetcode.cn/problems/add-two-numbers/) | 🟡 中等 | `while l1 or l2 or carry` 统一处理所有边界情况 | 2026-03-24 |
| 19 | [删除链表的倒数第 N 个节点](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/) | 🟡 中等 | - | - |
| 21 | [合并两个有序链表](https://leetcode.cn/problems/merge-two-sorted-lists/) | 🟢 简单 | dummy 节点作为假头，逐个比较合并 | 2026-03-24 |
| 23 | [合并 K 个升序链表](https://leetcode.cn/problems/merge-k-sorted-lists/) | 🔴 困难 | - | - |
| 24 | [两两交换链表中的节点](https://leetcode.cn/problems/swap-nodes-in-pairs/) | 🟡 中等 | - | - |
| 25 | [K 个一组翻转链表](https://leetcode.cn/problems/reverse-nodes-in-k-group/) | 🔴 困难 | - | - |
| 138 | [随机链表的复制](https://leetcode.cn/problems/copy-list-with-random-pointer/) | 🟡 中等 | - | - |
| 141 | [环形链表](https://leetcode.cn/problems/linked-list-cycle/) | 🟢 简单 | 快慢指针，有环则必相遇 | 2026-03-24 |
| 142 | [环形链表 II](https://leetcode.cn/problems/linked-list-cycle-ii/) | 🟡 中等 | 快慢指针求环长，双指针相距环长同步走找入口 | 2026-03-24 |
| 148 | [排序链表](https://leetcode.cn/problems/sort-list/) | 🟡 中等 | - | - |
| 160 | [相交链表](https://leetcode.cn/problems/intersection-of-two-linked-lists/) | 🟢 简单 | 双指针各走 a+c+b 和 b+c+a，必在交点或 None 相遇 | 2026-03-24 |
| 206 | [反转链表](https://leetcode.cn/problems/reverse-linked-list/) | 🟢 简单 | prev/cur/next_temp 三指针逐个反转 | 2026-03-24 |
| 234 | [回文链表](https://leetcode.cn/problems/palindrome-linked-list/) | 🟢 简单 | 快慢指针找中点，反转后半段，逐一比较 | 2026-03-24 |

---

## 二叉树

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 94 | [二叉树的中序遍历](https://leetcode.cn/problems/binary-tree-inorder-traversal/) | 🟢 简单 | - | - |
| 98 | [验证二叉搜索树](https://leetcode.cn/problems/validate-binary-search-tree/) | 🟡 中等 | - | - |
| 101 | [对称二叉树](https://leetcode.cn/problems/symmetric-tree/) | 🟢 简单 | - | - |
| 102 | [二叉树的层序遍历](https://leetcode.cn/problems/binary-tree-level-order-traversal/) | 🟡 中等 | - | - |
| 104 | [二叉树的最大深度](https://leetcode.cn/problems/maximum-depth-of-binary-tree/) | 🟢 简单 | - | - |
| 105 | [从前序与中序遍历序列构造二叉树](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | 🟡 中等 | - | - |
| 108 | [将有序数组转换为二叉搜索树](https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/) | 🟢 简单 | - | - |
| 114 | [二叉树展开为链表](https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/) | 🟡 中等 | - | - |
| 124 | [二叉树中的最大路径和](https://leetcode.cn/problems/binary-tree-maximum-path-sum/) | 🔴 困难 | - | - |
| 199 | [二叉树的右视图](https://leetcode.cn/problems/binary-tree-right-side-view/) | 🟡 中等 | - | - |
| 226 | [翻转二叉树](https://leetcode.cn/problems/invert-binary-tree/) | 🟢 简单 | - | - |
| 230 | [二叉搜索树中第 K 小的元素](https://leetcode.cn/problems/kth-smallest-element-in-a-bst/) | 🟡 中等 | - | - |
| 236 | [二叉树的最近公共祖先](https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/) | 🟡 中等 | - | - |
| 437 | [路径总和 III](https://leetcode.cn/problems/path-sum-iii/) | 🟡 中等 | - | - |
| 543 | [二叉树的直径](https://leetcode.cn/problems/diameter-of-binary-tree/) | 🟢 简单 | - | - |

---

## 图论

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 130 | [被围绕的区域](https://leetcode.cn/problems/surrounded-regions/) | 🟡 中等 | - | - |
| 200 | [岛屿数量](https://leetcode.cn/problems/number-of-islands/) | 🟡 中等 | - | - |
| 207 | [课程表](https://leetcode.cn/problems/course-schedule/) | 🟡 中等 | - | - |
| 208 | [实现 Trie (前缀树)](https://leetcode.cn/problems/implement-trie-prefix-tree/) | 🟡 中等 | - | - |
| 399 | [除法求值](https://leetcode.cn/problems/evaluate-division/) | 🟡 中等 | - | - |
| 994 | [腐烂的橘子](https://leetcode.cn/problems/rotting-oranges/) | 🟡 中等 | - | - |

---

## 回溯

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 17 | [电话号码的字母组合](https://leetcode.cn/problems/letter-combinations-of-a-phone-number/) | 🟡 中等 | - | - |
| 22 | [括号生成](https://leetcode.cn/problems/generate-parentheses/) | 🟡 中等 | - | - |
| 39 | [组合总和](https://leetcode.cn/problems/combination-sum/) | 🟡 中等 | - | - |
| 46 | [全排列](https://leetcode.cn/problems/permutations/) | 🟡 中等 | - | - |
| 51 | [N 皇后](https://leetcode.cn/problems/n-queens/) | 🔴 困难 | - | - |
| 78 | [子集](https://leetcode.cn/problems/subsets/) | 🟡 中等 | - | - |
| 79 | [单词搜索](https://leetcode.cn/problems/word-search/) | 🟡 中等 | - | - |
| 93 | [复原 IP 地址](https://leetcode.cn/problems/restore-ip-addresses/) | 🟡 中等 | - | - |
| 131 | [分割回文串](https://leetcode.cn/problems/palindrome-partitioning/) | 🟡 中等 | - | - |

---

## 二分查找

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 4 | [寻找两个正序数组的中位数](https://leetcode.cn/problems/median-of-two-sorted-arrays/) | 🔴 困难 | - | - |
| 33 | [搜索旋转排序数组](https://leetcode.cn/problems/search-in-rotated-sorted-array/) | 🟡 中等 | - | - |
| 34 | [在排序数组中查找元素的第一个和最后一个位置](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/) | 🟡 中等 | - | - |
| 35 | [搜索插入位置](https://leetcode.cn/problems/search-insert-position/) | 🟢 简单 | - | - |
| 74 | [搜索二维矩阵](https://leetcode.cn/problems/search-a-2d-matrix/) | 🟡 中等 | - | - |
| 153 | [寻找旋转排序数组中的最小值](https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/) | 🟡 中等 | - | - |

---

## 栈

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 20 | [有效的括号](https://leetcode.cn/problems/valid-parentheses/) | 🟢 简单 | - | - |
| 84 | [柱状图中最大的矩形](https://leetcode.cn/problems/largest-rectangle-in-histogram/) | 🔴 困难 | - | - |
| 155 | [最小栈](https://leetcode.cn/problems/min-stack/) | 🟡 中等 | - | - |
| 394 | [字符串解码](https://leetcode.cn/problems/decode-string/) | 🟡 中等 | - | - |
| 739 | [每日温度](https://leetcode.cn/problems/daily-temperatures/) | 🟡 中等 | - | - |

---

## 堆

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 215 | [数组中的第 K 个最大元素](https://leetcode.cn/problems/kth-largest-element-in-an-array/) | 🟡 中等 | - | - |
| 295 | [数据流的中位数](https://leetcode.cn/problems/find-median-from-data-stream/) | 🔴 困难 | - | - |
| 347 | [前 K 个高频元素](https://leetcode.cn/problems/top-k-frequent-elements/) | 🟡 中等 | - | - |

---

## 贪心

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 45 | [跳跃游戏 II](https://leetcode.cn/problems/jump-game-ii/) | 🟡 中等 | - | - |
| 55 | [跳跃游戏](https://leetcode.cn/problems/jump-game/) | 🟡 中等 | - | - |
| 121 | [买卖股票的最佳时机](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/) | 🟢 简单 | - | - |
| 135 | [分发糖果](https://leetcode.cn/problems/candy/) | 🔴 困难 | - | - |
| 406 | [根据身高重建队列](https://leetcode.cn/problems/queue-reconstruction-by-height/) | 🟡 中等 | - | - |
| 763 | [划分字母区间](https://leetcode.cn/problems/partition-labels/) | 🟡 中等 | - | - |

---

## 动态规划

| # | 题目 | 难度 | 思路 | 完成日期 |
|---|------|------|------|----------|
| 32 | [最长有效括号](https://leetcode.cn/problems/longest-valid-parentheses/) | 🔴 困难 | - | - |
| 70 | [爬楼梯](https://leetcode.cn/problems/climbing-stairs/) | 🟢 简单 | - | - |
| 72 | [编辑距离](https://leetcode.cn/problems/edit-distance/) | 🟡 中等 | - | - |
| 115 | [不同的子序列](https://leetcode.cn/problems/distinct-subsequences/) | 🔴 困难 | - | - |
| 118 | [杨辉三角](https://leetcode.cn/problems/pascals-triangle/) | 🟢 简单 | - | - |
| 139 | [单词拆分](https://leetcode.cn/problems/word-break/) | 🟡 中等 | - | - |
| 152 | [乘积最大子数组](https://leetcode.cn/problems/maximum-product-subarray/) | 🟡 中等 | - | - |
| 188 | [买卖股票的最佳时机 IV](https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/) | 🔴 困难 | - | - |
| 198 | [打家劫舍](https://leetcode.cn/problems/house-robber/) | 🟡 中等 | - | - |
| 221 | [最大正方形](https://leetcode.cn/problems/maximal-square/) | 🟡 中等 | - | - |
| 279 | [完全平方数](https://leetcode.cn/problems/perfect-squares/) | 🟡 中等 | - | - |
| 300 | [最长递增子序列](https://leetcode.cn/problems/longest-increasing-subsequence/) | 🟡 中等 | - | - |
| 322 | [零钱兑换](https://leetcode.cn/problems/coin-change/) | 🟡 中等 | - | - |
| 416 | [分割等和子集](https://leetcode.cn/problems/partition-equal-subset-sum/) | 🟡 中等 | - | - |
| 1143 | [最长公共子序列](https://leetcode.cn/problems/longest-common-subsequence/) | 🟡 中等 | - | - |

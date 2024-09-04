## SWE 100 questions 

<details>
<summary>Question 1 : Fizz Buzz</summary>

[View Question](https://leetcode.com/problems/fizz-buzz)

Given an integer `n`, return *a string array* `answer` *(**1\-indexed**) where*:

* `answer[i] == "FizzBuzz"` if `i` is divisible by `3` and `5`.
* `answer[i] == "Fizz"` if `i` is divisible by `3`.
* `answer[i] == "Buzz"` if `i` is divisible by `5`.
* `answer[i] == i` (as a string) if none of the above conditions are true.

**Example 1:**

```
Input: n = 3
Output: ["1","2","Fizz"]

```

**Example 2:**

```
Input: n = 5
Output: ["1","2","Fizz","4","Buzz"]

```

**Example 3:**

```
Input: n = 15
Output: ["1","2","Fizz","4","Buzz","Fizz","7","8","Fizz","Buzz","11","Fizz","13","14","FizzBuzz"]

```

**Constraints:**

* `1 <= n <= 104`

</details>

<details>
<summary>Question 2 : Two Sum</summary>

[View Question](https://leetcode.com/problems/two-sum)

Given an array of integers `nums` and an integer `target`, return *indices of the two numbers such that they add up
to `target`*.

You may assume that each input would have ***exactly* one solution**, and you may not use the *same* element twice.

You can return the answer in any order.

**Example 1:**

```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

```

**Example 2:**

```
Input: nums = [3,2,4], target = 6
Output: [1,2]

```

**Example 3:**

```
Input: nums = [3,3], target = 6
Output: [0,1]

```

**Constraints:**

* `2 <= nums.length <= 104`
* `-109 <= nums[i] <= 109`
* `-109 <= target <= 109`
* **Only one valid answer exists.**

**Follow\-up:**Can you come up with an algorithm that is less than `O(n2)` time complexity?

</details>

<details>
<summary>Question 3 : Valid Anagram</summary>

[View Question](https://leetcode.com/problems/valid-anagram)

Given two strings `s` and `t`, return `true` if `t` is an anagram of `s`, and `false` otherwise.

**Example 1:**

**Input:** s \= "anagram", t \= "nagaram"

**Output:** true

**Example 2:**

**Input:** s \= "rat", t \= "car"

**Output:** false

**Constraints:**

* `1 <= s.length, t.length <= 5 * 104`
* `s` and `t` consist of lowercase English letters.

**Follow up:** What if the inputs contain Unicode characters? How would you adapt your solution to such a case?




</details>

<details>
<summary>Question 4 : Reverse String</summary>

[View Question](https://leetcode.com/problems/reverse-string)

Write a function that reverses a string. The input string is given as an array of characters `s`.

You must do this by modifying the input array [in\-place](https://en.wikipedia.org/wiki/In-place_algorithm) with `O(1)`
extra memory.

**Example 1:**

```
Input: s = ["h","e","l","l","o"]
Output: ["o","l","l","e","h"]

```

**Example 2:**

```
Input: s = ["H","a","n","n","a","h"]
Output: ["h","a","n","n","a","H"]

```

**Constraints:**

* `1 <= s.length <= 105`
* `s[i]` is a [printable ascii character](https://en.wikipedia.org/wiki/ASCII#Printable_characters).

</details>

<details>
<summary>Question 5 : Valid Palindrome</summary>

[View Question](https://leetcode.com/problems/valid-palindrome)

A phrase is a **palindrome** if, after converting all uppercase letters into lowercase letters and removing all
non\-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and
numbers.

Given a string `s`, return `true` *if it is a **palindrome**, or* `false` *otherwise*.

**Example 1:**

```
Input: s = "A man, a plan, a canal: Panama"
Output: true
Explanation: "amanaplanacanalpanama" is a palindrome.

```

**Example 2:**

```
Input: s = "race a car"
Output: false
Explanation: "raceacar" is not a palindrome.

```

**Example 3:**

```
Input: s = " "
Output: true
Explanation: s is an empty string "" after removing non-alphanumeric characters.
Since an empty string reads the same forward and backward, it is a palindrome.

```

**Constraints:**

* `1 <= s.length <= 2 * 105`
* `s` consists only of printable ASCII characters.

</details>

<details>
<summary>Question 6 : Longest Common Prefix</summary>

[View Question](https://leetcode.com/problems/longest-common-prefix)

Write a function to find the longest common prefix string amongst an array of strings.

If there is no common prefix, return an empty string `""`.

**Example 1:**

```
Input: strs = ["flower","flow","flight"]
Output: "fl"

```

**Example 2:**

```
Input: strs = ["dog","racecar","car"]
Output: ""
Explanation: There is no common prefix among the input strings.

```

**Constraints:**

* `1 <= strs.length <= 200`
* `0 <= strs[i].length <= 200`
* `strs[i]` consists of only lowercase English letters.

</details>

<details>
<summary>Question 7 : Power of Three</summary>

[View Question](https://leetcode.com/problems/power-of-three)

Given an integer `n`, return *`true` if it is a power of three. Otherwise, return `false`*.

An integer `n` is a power of three, if there exists an integer `x` such that `n == 3x`.

**Example 1:**

```
Input: n = 27
Output: true
Explanation: 27 = 33

```

**Example 2:**

```
Input: n = 0
Output: false
Explanation: There is no x where 3x = 0.

```

**Example 3:**

```
Input: n = -1
Output: false
Explanation: There is no x where 3x = (-1).

```

**Constraints:**

* `-231 <= n <= 231 - 1`

**Follow up:** Could you solve it without loops/recursion?

</details>

<details>
<summary>Question 8 : Number of 1 Bits</summary>

[View Question](https://leetcode.com/problems/number-of-1-bits)

Write a function that takes the binary representation of a positive integer and returns the number of set bits it has (
also known as the [Hamming weight](http://en.wikipedia.org/wiki/Hamming_weight)).

**Example 1:**

**Input:** n \= 11

**Output:** 3

**Explanation:**

The input binary string **1011** has a total of three set bits.

**Example 2:**

**Input:** n \= 128

**Output:** 1

**Explanation:**

The input binary string **10000000** has a total of one set bit.

**Example 3:**

**Input:** n \= 2147483645

**Output:** 30

**Explanation:**

The input binary string **1111111111111111111111111111101** has a total of thirty set bits.

**Constraints:**

* `1 <= n <= 231 - 1`

**Follow up:** If this function is called many times, how would you optimize it?

</details>

<details>
<summary>Question 9 : Range Sum Query - Immutable</summary>

[View Question](https://leetcode.com/problems/range-sum-query-immutable)

Given an integer array `nums`, handle multiple queries of the following type:

1. Calculate the **sum** of the elements of `nums` between indices `left` and `right` **inclusive**
   where `left <= right`.

Implement the `NumArray` class:

* `NumArray(int[] nums)` Initializes the object with the integer array `nums`.
* `int sumRange(int left, int right)` Returns the **sum** of the elements of `nums` between indices `left` and `right` *
  *inclusive** (i.e. `nums[left] + nums[left + 1] + ... + nums[right]`).

**Example 1:**

```
Input
["NumArray", "sumRange", "sumRange", "sumRange"]
[[[-2, 0, 3, -5, 2, -1]], [0, 2], [2, 5], [0, 5]]
Output
[null, 1, -1, -3]

Explanation
NumArray numArray = new NumArray([-2, 0, 3, -5, 2, -1]);
numArray.sumRange(0, 2); // return (-2) + 0 + 3 = 1
numArray.sumRange(2, 5); // return 3 + (-5) + 2 + (-1) = -1
numArray.sumRange(0, 5); // return (-2) + 0 + 3 + (-5) + 2 + (-1) = -3

```

**Constraints:**

* `1 <= nums.length <= 104`
* `-105 <= nums[i] <= 105`
* `0 <= left <= right < nums.length`
* At most `104` calls will be made to `sumRange`.

</details>

<details>
<summary>Question 10 : Fibonacci Number</summary>

[View Question](https://leetcode.com/problems/fibonacci-number)

The **Fibonacci numbers**, commonly denoted `F(n)` form a sequence, called the **Fibonacci sequence**, such that each
number is the sum of the two preceding ones, starting from `0` and `1`. That is,

```
F(0) = 0, F(1) = 1
F(n) = F(n - 1) + F(n - 2), for n > 1.

```

Given `n`, calculate `F(n)`.

**Example 1:**

```
Input: n = 2
Output: 1
Explanation: F(2) = F(1) + F(0) = 1 + 0 = 1.

```

**Example 2:**

```
Input: n = 3
Output: 2
Explanation: F(3) = F(2) + F(1) = 1 + 1 = 2.

```

**Example 3:**

```
Input: n = 4
Output: 3
Explanation: F(4) = F(3) + F(2) = 2 + 1 = 3.

```

**Constraints:**

* `0 <= n <= 30`

</details>

<details>
<summary>Question 11 : Climbing Stairs</summary>

[View Question](https://leetcode.com/problems/climbing-stairs)

You are climbing a staircase. It takes `n` steps to reach the top.

Each time you can either climb `1` or `2` steps. In how many distinct ways can you climb to the top?

**Example 1:**

```
Input: n = 2
Output: 2
Explanation: There are two ways to climb to the top.
1. 1 step + 1 step
2. 2 steps

```

**Example 2:**

```
Input: n = 3
Output: 3
Explanation: There are three ways to climb to the top.
1. 1 step + 1 step + 1 step
2. 1 step + 2 steps
3. 2 steps + 1 step

```

**Constraints:**

* `1 <= n <= 45`

</details>

<details>
<summary>Question 12 : Min Cost Climbing Stairs</summary>

[View Question](https://leetcode.com/problems/min-cost-climbing-stairs)

You are given an integer array `cost` where `cost[i]` is the cost of `ith` step on a staircase. Once you pay the cost,
you can either climb one or two steps.

You can either start from the step with index `0`, or the step with index `1`.

Return *the minimum cost to reach the top of the floor*.

**Example 1:**

```
Input: cost = [10,15,20]
Output: 15
Explanation: You will start at index 1.
- Pay 15 and climb two steps to reach the top.
The total cost is 15.

```

**Example 2:**

```
Input: cost = [1,100,1,1,1,100,1,1,100,1]
Output: 6
Explanation: You will start at index 0.
- Pay 1 and climb two steps to reach index 2.
- Pay 1 and climb two steps to reach index 4.
- Pay 1 and climb two steps to reach index 6.
- Pay 1 and climb one step to reach index 7.
- Pay 1 and climb two steps to reach index 9.
- Pay 1 and climb one step to reach the top.
The total cost is 6.

```

**Constraints:**

* `2 <= cost.length <= 1000`
* `0 <= cost[i] <= 999`

</details>

<details>
<summary>Question 13 : Best Time to Buy and Sell Stock</summary>

[View Question](https://leetcode.com/problems/best-time-to-buy-and-sell-stock)

You are given an array `prices` where `prices[i]` is the price of a given stock on the `ith` day.

You want to maximize your profit by choosing a **single day** to buy one stock and choosing a **different day in the
future** to sell that stock.

Return *the maximum profit you can achieve from this transaction*. If you cannot achieve any profit, return `0`.

**Example 1:**

```
Input: prices = [7,1,5,3,6,4]
Output: 5
Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
Note that buying on day 2 and selling on day 1 is not allowed because you must buy before you sell.

```

**Example 2:**

```
Input: prices = [7,6,4,3,1]
Output: 0
Explanation: In this case, no transactions are done and the max profit = 0.

```

**Constraints:**

* `1 <= prices.length <= 105`
* `0 <= prices[i] <= 104`

</details>

<details>
<summary>Question 14 : Binary Tree Inorder Traversal</summary>

[View Question](https://leetcode.com/problems/binary-tree-inorder-traversal)

Given the `root` of a binary tree, return *the inorder traversal of its nodes' values*.

**Example 1:**

**Input:** root \= \[1,null,2,3]

**Output:** \[1,3,2]

**Explanation:**

![](https://assets.leetcode.com/uploads/2024/08/29/screenshot-2024-08-29-202743.png)

**Example 2:**

**Input:** root \= \[1,2,3,4,5,null,8,null,null,6,7,9]

**Output:** \[4,2,6,5,7,1,3,9,8]

**Explanation:**

![](https://assets.leetcode.com/uploads/2024/08/29/tree_2.png)

**Example 3:**

**Input:** root \= \[]

**Output:** \[]

**Example 4:**

**Input:** root \= \[1]

**Output:** \[1]

**Constraints:**

* The number of nodes in the tree is in the range `[0, 100]`.
* `-100 <= Node.val <= 100`

**Follow up:** Recursive solution is trivial, could you do it iteratively?

</details>

<details>
<summary>Question 15 : Invert Binary Tree</summary>

[View Question](https://leetcode.com/problems/invert-binary-tree)

Given the `root` of a binary tree, invert the tree, and return *its root*.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/03/14/invert1-tree.jpg)

```
Input: root = [4,2,7,1,3,6,9]
Output: [4,7,2,9,6,3,1]

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/03/14/invert2-tree.jpg)

```
Input: root = [2,1,3]
Output: [2,3,1]

```

**Example 3:**

```
Input: root = []
Output: []

```

**Constraints:**

* The number of nodes in the tree is in the range `[0, 100]`.
* `-100 <= Node.val <= 100`

</details>

<details>
<summary>Question 16 : Symmetric Tree</summary>

[View Question](https://leetcode.com/problems/symmetric-tree)

Given the `root` of a binary tree, *check whether it is a mirror of itself* (i.e., symmetric around its center).

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/02/19/symtree1.jpg)

```
Input: root = [1,2,2,3,4,4,3]
Output: true

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/02/19/symtree2.jpg)

```
Input: root = [1,2,2,null,3,null,3]
Output: false

```

**Constraints:**

* The number of nodes in the tree is in the range `[1, 1000]`.
* `-100 <= Node.val <= 100`

**Follow up:** Could you solve it both recursively and iteratively?

</details>

<details>
<summary>Question 17 : Maximum Depth of Binary Tree</summary>

[View Question](https://leetcode.com/problems/maximum-depth-of-binary-tree)

Given the `root` of a binary tree, return *its maximum depth*.

A binary tree's **maximum depth** is the number of nodes along the longest path from the root node down to the farthest
leaf node.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/11/26/tmp-tree.jpg)

```
Input: root = [3,9,20,null,null,15,7]
Output: 3

```

**Example 2:**

```
Input: root = [1,null,2]
Output: 2

```

**Constraints:**

* The number of nodes in the tree is in the range `[0, 104]`.
* `-100 <= Node.val <= 100`

</details>

<details>
<summary>Question 18 : Same Tree</summary>

[View Question](https://leetcode.com/problems/same-tree)

Given the roots of two binary trees `p` and `q`, write a function to check if they are the same or not.

Two binary trees are considered the same if they are structurally identical, and the nodes have the same value.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/12/20/ex1.jpg)

```
Input: p = [1,2,3], q = [1,2,3]
Output: true

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/12/20/ex2.jpg)

```
Input: p = [1,2], q = [1,null,2]
Output: false

```

**Example 3:**

![](https://assets.leetcode.com/uploads/2020/12/20/ex3.jpg)

```
Input: p = [1,2,1], q = [1,1,2]
Output: false

```

**Constraints:**

* The number of nodes in both trees is in the range `[0, 100]`.
* `-104 <= Node.val <= 104`

</details>

<details>
<summary>Question 19 : Path Sum</summary>

[View Question](https://leetcode.com/problems/path-sum)

Given the `root` of a binary tree and an integer `targetSum`, return `true` if the tree has a **root\-to\-leaf** path
such that adding up all the values along the path equals `targetSum`.

A **leaf** is a node with no children.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/01/18/pathsum1.jpg)

```
Input: root = [5,4,8,11,null,13,4,7,2,null,null,null,1], targetSum = 22
Output: true
Explanation: The root-to-leaf path with the target sum is shown.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/01/18/pathsum2.jpg)

```
Input: root = [1,2,3], targetSum = 5
Output: false
Explanation: There two root-to-leaf paths in the tree:
(1 --> 2): The sum is 3.
(1 --> 3): The sum is 4.
There is no root-to-leaf path with sum = 5.

```

**Example 3:**

```
Input: root = [], targetSum = 0
Output: false
Explanation: Since the tree is empty, there are no root-to-leaf paths.

```

**Constraints:**

* The number of nodes in the tree is in the range `[0, 5000]`.
* `-1000 <= Node.val <= 1000`
* `-1000 <= targetSum <= 1000`

</details>

<details>
<summary>Question 20 : Minimum Depth of Binary Tree</summary>

[View Question](https://leetcode.com/problems/minimum-depth-of-binary-tree)

Given a binary tree, find its minimum depth.

The minimum depth is the number of nodes along the shortest path from the root node down to the nearest leaf node.

**Note:** A leaf is a node with no children.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/10/12/ex_depth.jpg)

```
Input: root = [3,9,20,null,null,15,7]
Output: 2

```

**Example 2:**

```
Input: root = [2,null,3,null,4,null,5,null,6]
Output: 5

```

**Constraints:**

* The number of nodes in the tree is in the range `[0, 105]`.
* `-1000 <= Node.val <= 1000`

</details>

<details>
<summary>Question 21 : Validate Binary Search Tree</summary>

[View Question](https://leetcode.com/problems/validate-binary-search-tree)

Given the `root` of a binary tree, *determine if it is a valid binary search tree (BST)*.

A **valid BST** is defined as follows:

* The left subtree of a node contains only nodes with keys **less than** the node's key.
* The right subtree of a node contains only nodes with keys **greater than** the node's key.
* Both the left and right subtrees must also be binary search trees.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/12/01/tree1.jpg)

```
Input: root = [2,1,3]
Output: true

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/12/01/tree2.jpg)

```
Input: root = [5,1,4,null,null,3,6]
Output: false
Explanation: The root node's value is 5 but its right child's value is 4.

```

**Constraints:**

* The number of nodes in the tree is in the range `[1, 104]`.
* `-231 <= Node.val <= 231 - 1`

</details>

<details>
<summary>Question 22 : Reverse Linked List</summary>

[View Question](https://leetcode.com/problems/reverse-linked-list)

Given the `head` of a singly linked list, reverse the list, and return *the reversed list*.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/02/19/rev1ex1.jpg)

```
Input: head = [1,2,3,4,5]
Output: [5,4,3,2,1]

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/02/19/rev1ex2.jpg)

```
Input: head = [1,2]
Output: [2,1]

```

**Example 3:**

```
Input: head = []
Output: []

```

**Constraints:**

* The number of nodes in the list is the range `[0, 5000]`.
* `-5000 <= Node.val <= 5000`

**Follow up:** A linked list can be reversed either iteratively or recursively. Could you implement both?




</details>

<details>
<summary>Question 23 : Middle of the Linked List</summary>

[View Question](https://leetcode.com/problems/middle-of-the-linked-list)

Given the `head` of a singly linked list, return *the middle node of the linked list*.

If there are two middle nodes, return **the second middle** node.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/07/23/lc-midlist1.jpg)

```
Input: head = [1,2,3,4,5]
Output: [3,4,5]
Explanation: The middle node of the list is node 3.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/07/23/lc-midlist2.jpg)

```
Input: head = [1,2,3,4,5,6]
Output: [4,5,6]
Explanation: Since the list has two middle nodes with values 3 and 4, we return the second one.

```

**Constraints:**

* The number of nodes in the list is in the range `[1, 100]`.
* `1 <= Node.val <= 100`

</details>

<details>
<summary>Question 24 : Binary Tree Level Order Traversal</summary>

[View Question](https://leetcode.com/problems/binary-tree-level-order-traversal)

Given the `root` of a binary tree, return *the level order traversal of its nodes' values*. (i.e., from left to right,
level by level).

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/02/19/tree1.jpg)

```
Input: root = [3,9,20,null,null,15,7]
Output: [[3],[9,20],[15,7]]

```

**Example 2:**

```
Input: root = [1]
Output: [[1]]

```

**Example 3:**

```
Input: root = []
Output: []

```

**Constraints:**

* The number of nodes in the tree is in the range `[0, 2000]`.
* `-1000 <= Node.val <= 1000`

</details>

<details>
<summary>Question 25 : Find if Path Exists in Graph</summary>

[View Question](https://leetcode.com/problems/find-if-path-exists-in-graph)

There is a **bi\-directional** graph with `n` vertices, where each vertex is labeled from `0` to `n - 1` (**inclusive
**). The edges in the graph are represented as a 2D integer array `edges`, where each `edges[i] = [ui, vi]` denotes a
bi\-directional edge between vertex `ui` and vertex `vi`. Every vertex pair is connected by **at most one** edge, and no
vertex has an edge to itself.

You want to determine if there is a **valid path** that exists from vertex `source` to vertex `destination`.

Given `edges` and the integers `n`, `source`, and `destination`, return `true` *if there is a **valid path**
from* `source` *to* `destination`*, or* `false` *otherwise**.*

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/08/14/validpath-ex1.png)

```
Input: n = 3, edges = [[0,1],[1,2],[2,0]], source = 0, destination = 2
Output: true
Explanation: There are two paths from vertex 0 to vertex 2:
- 0 → 1 → 2
- 0 → 2

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/08/14/validpath-ex2.png)

```
Input: n = 6, edges = [[0,1],[0,2],[3,5],[5,4],[4,3]], source = 0, destination = 5
Output: false
Explanation: There is no path from vertex 0 to vertex 5.

```

**Constraints:**

* `1 <= n <= 2 * 105`
* `0 <= edges.length <= 2 * 105`
* `edges[i].length == 2`
* `0 <= ui, vi <= n - 1`
* `ui != vi`
* `0 <= source, destination <= n - 1`
* There are no duplicate edges.
* There are no self edges.

</details>

<details>
<summary>Question 26 : Number of Islands</summary>

[View Question](https://leetcode.com/problems/number-of-islands)

Given an `m x n` 2D binary grid `grid` which represents a map of `'1'`s (land) and `'0'`s (water), return *the number of
islands*.

An **island** is surrounded by water and is formed by connecting adjacent lands horizontally or vertically. You may
assume all four edges of the grid are all surrounded by water.

**Example 1:**

```
Input: grid = [
  ["1","1","1","1","0"],
  ["1","1","0","1","0"],
  ["1","1","0","0","0"],
  ["0","0","0","0","0"]
]
Output: 1

```

**Example 2:**

```
Input: grid = [
  ["1","1","0","0","0"],
  ["1","1","0","0","0"],
  ["0","0","1","0","0"],
  ["0","0","0","1","1"]
]
Output: 3

```

**Constraints:**

* `m == grid.length`
* `n == grid[i].length`
* `1 <= m, n <= 300`
* `grid[i][j]` is `'0'` or `'1'`.

</details>

<details>
<summary>Question 27 : Max Area of Island</summary>

[View Question](https://leetcode.com/problems/max-area-of-island)

You are given an `m x n` binary matrix `grid`. An island is a group of `1`'s (representing land) connected *
*4\-directionally** (horizontal or vertical.) You may assume all four edges of the grid are surrounded by water.

The **area** of an island is the number of cells with a value `1` in the island.

Return *the maximum **area** of an island in* `grid`. If there is no island, return `0`.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/05/01/maxarea1-grid.jpg)

```
Input: grid = [[0,0,1,0,0,0,0,1,0,0,0,0,0],[0,0,0,0,0,0,0,1,1,1,0,0,0],[0,1,1,0,1,0,0,0,0,0,0,0,0],[0,1,0,0,1,1,0,0,1,0,1,0,0],[0,1,0,0,1,1,0,0,1,1,1,0,0],[0,0,0,0,0,0,0,0,0,0,1,0,0],[0,0,0,0,0,0,0,1,1,1,0,0,0],[0,0,0,0,0,0,0,1,1,0,0,0,0]]
Output: 6
Explanation: The answer is not 11, because the island must be connected 4-directionally.

```

**Example 2:**

```
Input: grid = [[0,0,0,0,0,0,0,0]]
Output: 0

```

**Constraints:**

* `m == grid.length`
* `n == grid[i].length`
* `1 <= m, n <= 50`
* `grid[i][j]` is either `0` or `1`.

</details>

<details>
<summary>Question 28 : Count Sub Islands</summary>

[View Question](https://leetcode.com/problems/count-sub-islands)

You are given two `m x n` binary matrices `grid1` and `grid2` containing only `0`'s (representing water) and `1`'s (
representing land). An **island** is a group of `1`'s connected **4\-directionally** (horizontal or vertical). Any cells
outside of the grid are considered water cells.

An island in `grid2` is considered a **sub\-island** if there is an island in `grid1` that contains **all** the cells
that make up **this** island in `grid2`.

Return the ***number** of islands in* `grid2` *that are considered **sub\-islands***.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/06/10/test1.png)

```
Input: grid1 = [[1,1,1,0,0],[0,1,1,1,1],[0,0,0,0,0],[1,0,0,0,0],[1,1,0,1,1]], grid2 = [[1,1,1,0,0],[0,0,1,1,1],[0,1,0,0,0],[1,0,1,1,0],[0,1,0,1,0]]
Output: 3
Explanation: In the picture above, the grid on the left is grid1 and the grid on the right is grid2.
The 1s colored red in grid2 are those considered to be part of a sub-island. There are three sub-islands.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/06/03/testcasex2.png)

```
Input: grid1 = [[1,0,1,0,1],[1,1,1,1,1],[0,0,0,0,0],[1,1,1,1,1],[1,0,1,0,1]], grid2 = [[0,0,0,0,0],[1,1,1,1,1],[0,1,0,1,0],[0,1,0,1,0],[1,0,0,0,1]]
Output: 2 
Explanation: In the picture above, the grid on the left is grid1 and the grid on the right is grid2.
The 1s colored red in grid2 are those considered to be part of a sub-island. There are two sub-islands.

```

**Constraints:**

* `m == grid1.length == grid2.length`
* `n == grid1[i].length == grid2[i].length`
* `1 <= m, n <= 500`
* `grid1[i][j]` and `grid2[i][j]` are either `0` or `1`.

</details>

<details>
<summary>Question 29 : Valid Parentheses</summary>

[View Question](https://leetcode.com/problems/valid-parentheses)

Given a string `s` containing just the characters `'('`, `')'`, `'{'`, `'}'`, `'['` and `']'`, determine if the input
string is valid.

An input string is valid if:

1. Open brackets must be closed by the same type of brackets.
2. Open brackets must be closed in the correct order.
3. Every close bracket has a corresponding open bracket of the same type.

**Example 1:**

**Input:** s \= "()"

**Output:** true

**Example 2:**

**Input:** s \= "()\[]{}"

**Output:** true

**Example 3:**

**Input:** s \= "(]"

**Output:** false

**Example 4:**

**Input:** s \= "(\[])"

**Output:** true

**Constraints:**

* `1 <= s.length <= 104`
* `s` consists of parentheses only `'()[]{}'`.

</details>

<details>
<summary>Question 30 : Product of Array Except Self</summary>

[View Question](https://leetcode.com/problems/product-of-array-except-self)

Given an integer array `nums`, return *an array* `answer` *such that* `answer[i]` *is equal to the product of all the
elements of* `nums` *except* `nums[i]`.

The product of any prefix or suffix of `nums` is **guaranteed** to fit in a **32\-bit** integer.

You must write an algorithm that runs in `O(n)` time and without using the division operation.

**Example 1:**

```
Input: nums = [1,2,3,4]
Output: [24,12,8,6]

```

**Example 2:**

```
Input: nums = [-1,1,0,-3,3]
Output: [0,0,9,0,0]

```

**Constraints:**

* `2 <= nums.length <= 105`
* `-30 <= nums[i] <= 30`
* The product of any prefix or suffix of `nums` is **guaranteed** to fit in a **32\-bit** integer.

**Follow up:** Can you solve the problem in `O(1)` extra space complexity? (The output array **does not** count as extra
space for space complexity analysis.)




</details>

<details>
<summary>Question 31 : Binary Search</summary>

[View Question](https://leetcode.com/problems/binary-search)

Given an array of integers `nums` which is sorted in ascending order, and an integer `target`, write a function to
search `target` in `nums`. If `target` exists, then return its index. Otherwise, return `-1`.

You must write an algorithm with `O(log n)` runtime complexity.

**Example 1:**

```
Input: nums = [-1,0,3,5,9,12], target = 9
Output: 4
Explanation: 9 exists in nums and its index is 4

```

**Example 2:**

```
Input: nums = [-1,0,3,5,9,12], target = 2
Output: -1
Explanation: 2 does not exist in nums so return -1

```

**Constraints:**

* `1 <= nums.length <= 104`
* `-104 < nums[i], target < 104`
* All the integers in `nums` are **unique**.
* `nums` is sorted in ascending order.

</details>

<details>
<summary>Question 32 : Minimum Add to Make Parentheses Valid</summary>

[View Question](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid)

A parentheses string is valid if and only if:

* It is the empty string,
* It can be written as `AB` (`A` concatenated with `B`), where `A` and `B` are valid strings, or
* It can be written as `(A)`, where `A` is a valid string.

You are given a parentheses string `s`. In one move, you can insert a parenthesis at any position of the string.

* For example, if `s = "()))"`, you can insert an opening parenthesis to be `"(()))"` or a closing parenthesis to
  be `"())))"`.

Return *the minimum number of moves required to make* `s` *valid*.

**Example 1:**

```
Input: s = "())"
Output: 1

```

**Example 2:**

```
Input: s = "((("
Output: 3

```

**Constraints:**

* `1 <= s.length <= 1000`
* `s[i]` is either `'('` or `')'`.

</details>

<details>
<summary>Question 33 : Longest Palindromic Substring</summary>

[View Question](https://leetcode.com/problems/longest-palindromic-substring)

Given a string `s`, return *the longest* *palindromic* *substring* in `s`.

**Example 1:**

```
Input: s = "babad"
Output: "bab"
Explanation: "aba" is also a valid answer.

```

**Example 2:**

```
Input: s = "cbbd"
Output: "bb"

```

**Constraints:**

* `1 <= s.length <= 1000`
* `s` consist of only digits and English letters.

</details>

<details>
<summary>Question 34 : Two Sum II - Input Array Is Sorted</summary>

[View Question](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted)

Given a **1\-indexed** array of integers `numbers` that is already ***sorted in non\-decreasing order***, find two
numbers such that they add up to a specific `target` number. Let these two numbers be `numbers[index1]`
and `numbers[index2]` where `1 <= index1 < index2 <= numbers.length`.

Return *the indices of the two numbers,* `index1` *and* `index2`*, **added by one** as an integer
array* `[index1, index2]` *of length 2\.*

The tests are generated such that there is **exactly one solution**. You **may not** use the same element twice.

Your solution must use only constant extra space.

**Example 1:**

```
Input: numbers = [2,7,11,15], target = 9
Output: [1,2]
Explanation: The sum of 2 and 7 is 9. Therefore, index1 = 1, index2 = 2. We return [1, 2].

```

**Example 2:**

```
Input: numbers = [2,3,4], target = 6
Output: [1,3]
Explanation: The sum of 2 and 4 is 6. Therefore index1 = 1, index2 = 3. We return [1, 3].

```

**Example 3:**

```
Input: numbers = [-1,0], target = -1
Output: [1,2]
Explanation: The sum of -1 and 0 is -1. Therefore index1 = 1, index2 = 2. We return [1, 2].

```

**Constraints:**

* `2 <= numbers.length <= 3 * 104`
* `-1000 <= numbers[i] <= 1000`
* `numbers` is sorted in **non\-decreasing order**.
* `-1000 <= target <= 1000`
* The tests are generated such that there is **exactly one solution**.

</details>

<details>
<summary>Question 35 : Container With Most Water</summary>

[View Question](https://leetcode.com/problems/container-with-most-water)

You are given an integer array `height` of length `n`. There are `n` vertical lines drawn such that the two endpoints of
the `ith` line are `(i, 0)` and `(i, height[i])`.

Find two lines that together with the x\-axis form a container, such that the container contains the most water.

Return *the maximum amount of water a container can store*.

**Notice** that you may not slant the container.

**Example 1:**

![](https://s3-lc-upload.s3.amazonaws.com/uploads/2018/07/17/question_11.jpg)

```
Input: height = [1,8,6,2,5,4,8,3,7]
Output: 49
Explanation: The above vertical lines are represented by array [1,8,6,2,5,4,8,3,7]. In this case, the max area of water (blue section) the container can contain is 49.

```

**Example 2:**

```
Input: height = [1,1]
Output: 1

```

**Constraints:**

* `n == height.length`
* `2 <= n <= 105`
* `0 <= height[i] <= 104`

</details>

<details>
<summary>Question 36 : 3Sum</summary>

[View Question](https://leetcode.com/problems/3sum)

Given an integer array nums, return all the triplets `[nums[i], nums[j], nums[k]]` such that `i != j`, `i != k`,
and `j != k`, and `nums[i] + nums[j] + nums[k] == 0`.

Notice that the solution set must not contain duplicate triplets.

**Example 1:**

```
Input: nums = [-1,0,1,2,-1,-4]
Output: [[-1,-1,2],[-1,0,1]]
Explanation: 
nums[0] + nums[1] + nums[2] = (-1) + 0 + 1 = 0.
nums[1] + nums[2] + nums[4] = 0 + 1 + (-1) = 0.
nums[0] + nums[3] + nums[4] = (-1) + 2 + (-1) = 0.
The distinct triplets are [-1,0,1] and [-1,-1,2].
Notice that the order of the output and the order of the triplets does not matter.

```

**Example 2:**

```
Input: nums = [0,1,1]
Output: []
Explanation: The only possible triplet does not sum up to 0.

```

**Example 3:**

```
Input: nums = [0,0,0]
Output: [[0,0,0]]
Explanation: The only possible triplet sums up to 0.

```

**Constraints:**

* `3 <= nums.length <= 3000`
* `-105 <= nums[i] <= 105`

</details>

<details>
<summary>Question 37 : Group Anagrams</summary>

[View Question](https://leetcode.com/problems/group-anagrams)

Given an array of strings `strs`, group the anagrams together. You can return the answer in **any order**.

**Example 1:**

**Input:** strs \= \["eat","tea","tan","ate","nat","bat"]

**Output:** \[\["bat"],\["nat","tan"],\["ate","eat","tea"]]

**Explanation:**

* There is no string in strs that can be rearranged to form `"bat"`.
* The strings `"nat"` and `"tan"` are anagrams as they can be rearranged to form each other.
* The strings `"ate"`, `"eat"`, and `"tea"` are anagrams as they can be rearranged to form each other.

**Example 2:**

**Input:** strs \= \[""]

**Output:** \[\[""]]

**Example 3:**

**Input:** strs \= \["a"]

**Output:** \[\["a"]]

**Constraints:**

* `1 <= strs.length <= 104`
* `0 <= strs[i].length <= 100`
* `strs[i]` consists of lowercase English letters.

</details>

<details>
<summary>Question 38 : Kth Largest Element in an Array</summary>

[View Question](https://leetcode.com/problems/kth-largest-element-in-an-array)

Given an integer array `nums` and an integer `k`, return *the* `kth` *largest element in the array*.

Note that it is the `kth` largest element in the sorted order, not the `kth` distinct element.

Can you solve it without sorting?

**Example 1:**

```
Input: nums = [3,2,1,5,6,4], k = 2
Output: 5

```

**Example 2:**

```
Input: nums = [3,2,3,1,2,4,5,5,6], k = 4
Output: 4

```

**Constraints:**

* `1 <= k <= nums.length <= 105`
* `-104 <= nums[i] <= 104`

</details>

<details>
<summary>Question 39 : K Closest Points to Origin</summary>

[View Question](https://leetcode.com/problems/k-closest-points-to-origin)

Given an array of `points` where `points[i] = [xi, yi]` represents a point on the **X\-Y** plane and an integer `k`,
return the `k` closest points to the origin `(0, 0)`.

The distance between two points on the **X\-Y** plane is the Euclidean distance (i.e., `√(x1 - x2)2 + (y1 - y2)2`).

You may return the answer in **any order**. The answer is **guaranteed** to be **unique** (except for the order that it
is in).

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/03/03/closestplane1.jpg)

```
Input: points = [[1,3],[-2,2]], k = 1
Output: [[-2,2]]
Explanation:
The distance between (1, 3) and the origin is sqrt(10).
The distance between (-2, 2) and the origin is sqrt(8).
Since sqrt(8) < sqrt(10), (-2, 2) is closer to the origin.
We only want the closest k = 1 points from the origin, so the answer is just [[-2,2]].

```

**Example 2:**

```
Input: points = [[3,3],[5,-1],[-2,4]], k = 2
Output: [[3,3],[-2,4]]
Explanation: The answer [[-2,4],[3,3]] would also be accepted.

```

**Constraints:**

* `1 <= k <= points.length <= 104`
* `-104 <= xi, yi <= 104`

</details>

<details>
<summary>Question 40 : Insert Delete GetRandom O(1)</summary>

[View Question](https://leetcode.com/problems/insert-delete-getrandom-o1)

Implement the `RandomizedSet` class:

* `RandomizedSet()` Initializes the `RandomizedSet` object.
* `bool insert(int val)` Inserts an item `val` into the set if not present. Returns `true` if the item was not
  present, `false` otherwise.
* `bool remove(int val)` Removes an item `val` from the set if present. Returns `true` if the item was present, `false`
  otherwise.
* `int getRandom()` Returns a random element from the current set of elements (it's guaranteed that at least one element
  exists when this method is called). Each element must have the **same probability** of being returned.

You must implement the functions of the class such that each function works in **average** `O(1)` time complexity.

**Example 1:**

```
Input
["RandomizedSet", "insert", "remove", "insert", "getRandom", "remove", "insert", "getRandom"]
[[], [1], [2], [2], [], [1], [2], []]
Output
[null, true, false, true, 2, true, false, 2]

Explanation
RandomizedSet randomizedSet = new RandomizedSet();
randomizedSet.insert(1); // Inserts 1 to the set. Returns true as 1 was inserted successfully.
randomizedSet.remove(2); // Returns false as 2 does not exist in the set.
randomizedSet.insert(2); // Inserts 2 to the set, returns true. Set now contains [1,2].
randomizedSet.getRandom(); // getRandom() should return either 1 or 2 randomly.
randomizedSet.remove(1); // Removes 1 from the set, returns true. Set now contains [2].
randomizedSet.insert(2); // 2 was already in the set, so return false.
randomizedSet.getRandom(); // Since 2 is the only number in the set, getRandom() will always return 2.

```

**Constraints:**

* `-231 <= val <= 231 - 1`
* At most `2 *``105` calls will be made to `insert`, `remove`, and `getRandom`.
* There will be **at least one** element in the data structure when `getRandom` is called.

</details>

<details>
<summary>Question 41 : First Bad Version</summary>

[View Question](https://leetcode.com/problems/first-bad-version)

You are a product manager and currently leading a team to develop a new product. Unfortunately, the latest version of
your product fails the quality check. Since each version is developed based on the previous version, all the versions
after a bad version are also bad.

Suppose you have `n` versions `[1, 2, ..., n]` and you want to find out the first bad one, which causes all the
following ones to be bad.

You are given an API `bool isBadVersion(version)` which returns whether `version` is bad. Implement a function to find
the first bad version. You should minimize the number of calls to the API.

**Example 1:**

```
Input: n = 5, bad = 4
Output: 4
Explanation:
call isBadVersion(3) -> false
call isBadVersion(5) -> true
call isBadVersion(4) -> true
Then 4 is the first bad version.

```

**Example 2:**

```
Input: n = 1, bad = 1
Output: 1

```

**Constraints:**

* `1 <= bad <= n <= 231 - 1`

</details>

<details>
<summary>Question 42 : Find Peak Element</summary>

[View Question](https://leetcode.com/problems/find-peak-element)

A peak element is an element that is strictly greater than its neighbors.

Given a **0\-indexed** integer array `nums`, find a peak element, and return its index. If the array contains multiple
peaks, return the index to **any of the peaks**.

You may imagine that `nums[-1] = nums[n] = -∞`. In other words, an element is always considered to be strictly greater
than a neighbor that is outside the array.

You must write an algorithm that runs in `O(log n)` time.

**Example 1:**

```
Input: nums = [1,2,3,1]
Output: 2
Explanation: 3 is a peak element and your function should return the index number 2.
```

**Example 2:**

```
Input: nums = [1,2,1,3,5,6,4]
Output: 5
Explanation: Your function can return either index number 1 where the peak element is 2, or index number 5 where the peak element is 6.
```

**Constraints:**

* `1 <= nums.length <= 1000`
* `-231 <= nums[i] <= 231 - 1`
* `nums[i] != nums[i + 1]` for all valid `i`.

</details>

<details>
<summary>Question 43 : Sqrt(x)</summary>

[View Question](https://leetcode.com/problems/sqrtx)

Given a non\-negative integer `x`, return *the square root of* `x` *rounded down to the nearest integer*. The returned
integer should be **non\-negative** as well.

You **must not use** any built\-in exponent function or operator.

* For example, do not use `pow(x, 0.5)` in c\+\+ or `x ** 0.5` in python.

**Example 1:**

```
Input: x = 4
Output: 2
Explanation: The square root of 4 is 2, so we return 2.

```

**Example 2:**

```
Input: x = 8
Output: 2
Explanation: The square root of 8 is 2.82842..., and since we round it down to the nearest integer, 2 is returned.

```

**Constraints:**

* `0 <= x <= 231 - 1`

</details>

<details>
<summary>Question 44 : Koko Eating Bananas</summary>

[View Question](https://leetcode.com/problems/koko-eating-bananas)

Koko loves to eat bananas. There are `n` piles of bananas, the `ith` pile has `piles[i]` bananas. The guards have gone
and will come back in `h` hours.

Koko can decide her bananas\-per\-hour eating speed of `k`. Each hour, she chooses some pile of bananas and eats `k`
bananas from that pile. If the pile has less than `k` bananas, she eats all of them instead and will not eat any more
bananas during this hour.

Koko likes to eat slowly but still wants to finish eating all the bananas before the guards return.

Return *the minimum integer* `k` *such that she can eat all the bananas within* `h` *hours*.

**Example 1:**

```
Input: piles = [3,6,7,11], h = 8
Output: 4

```

**Example 2:**

```
Input: piles = [30,11,23,4,20], h = 5
Output: 30

```

**Example 3:**

```
Input: piles = [30,11,23,4,20], h = 6
Output: 23

```

**Constraints:**

* `1 <= piles.length <= 104`
* `piles.length <= h <= 109`
* `1 <= piles[i] <= 109`

</details>

<details>
<summary>Question 45 : Subarray Sum Equals K</summary>

[View Question](https://leetcode.com/problems/subarray-sum-equals-k)

Given an array of integers `nums` and an integer `k`, return *the total number of subarrays whose sum equals to* `k`.

A subarray is a contiguous **non\-empty** sequence of elements within an array.

**Example 1:**

```
Input: nums = [1,1,1], k = 2
Output: 2

```

**Example 2:**

```
Input: nums = [1,2,3], k = 3
Output: 2

```

**Constraints:**

* `1 <= nums.length <= 2 * 104`
* `-1000 <= nums[i] <= 1000`
* `-107 <= k <= 107`

</details>

<details>
<summary>Question 46 : Continuous Subarray Sum</summary>

[View Question](https://leetcode.com/problems/continuous-subarray-sum)

Given an integer array nums and an integer k, return `true` *if* `nums` *has a **good subarray** or* `false`
*otherwise*.

A **good subarray** is a subarray where:

* its length is **at least two**, and
* the sum of the elements of the subarray is a multiple of `k`.

**Note** that:

* A **subarray** is a contiguous part of the array.
* An integer `x` is a multiple of `k` if there exists an integer `n` such that `x = n * k`. `0` is **always** a multiple
  of `k`.

**Example 1:**

```
Input: nums = [23,2,4,6,7], k = 6
Output: true
Explanation: [2, 4] is a continuous subarray of size 2 whose elements sum up to 6.

```

**Example 2:**

```
Input: nums = [23,2,6,4,7], k = 6
Output: true
Explanation: [23, 2, 6, 4, 7] is an continuous subarray of size 5 whose elements sum up to 42.
42 is a multiple of 6 because 42 = 7 * 6 and 7 is an integer.

```

**Example 3:**

```
Input: nums = [23,2,6,4,7], k = 13
Output: false

```

**Constraints:**

* `1 <= nums.length <= 105`
* `0 <= nums[i] <= 109`
* `0 <= sum(nums[i]) <= 231 - 1`
* `1 <= k <= 231 - 1`

</details>

<details>
<summary>Question 47 : Count Number of Nice Subarrays</summary>

[View Question](https://leetcode.com/problems/count-number-of-nice-subarrays)

Given an array of integers `nums` and an integer `k`. A continuous subarray is called **nice** if there are `k` odd
numbers on it.

Return *the number of **nice** sub\-arrays*.

**Example 1:**

```
Input: nums = [1,1,2,1,1], k = 3
Output: 2
Explanation: The only sub-arrays with 3 odd numbers are [1,1,2,1] and [1,2,1,1].

```

**Example 2:**

```
Input: nums = [2,4,6], k = 1
Output: 0
Explanation: There are no odd numbers in the array.

```

**Example 3:**

```
Input: nums = [2,2,2,1,2,2,1,2,2,2], k = 2
Output: 16

```

**Constraints:**

* `1 <= nums.length <= 50000`
* `1 <= nums[i] <= 10^5`
* `1 <= k <= nums.length`

</details>

<details>
<summary>Question 48 : Clone Graph</summary>

[View Question](https://leetcode.com/problems/clone-graph)

Given a reference of a node in a *
*[connected](https://en.wikipedia.org/wiki/Connectivity_(graph_theory)#Connected_graph)** undirected graph.

Return a [**deep copy**](https://en.wikipedia.org/wiki/Object_copying#Deep_copy) (clone) of the graph.

Each node in the graph contains a value (`int`) and a list (`List[Node]`) of its neighbors.

```
class Node {
    public int val;
    public List<Node> neighbors;
}

```

**Test case format:**

For simplicity, each node's value is the same as the node's index (1\-indexed). For example, the first node
with `val == 1`, the second node with `val == 2`, and so on. The graph is represented in the test case using an
adjacency list.

**An adjacency list** is a collection of unordered **lists** used to represent a finite graph. Each list describes the
set of neighbors of a node in the graph.

The given node will always be the first node with `val = 1`. You must return the **copy of the given node** as a
reference to the cloned graph.

**Example 1:**

![](https://assets.leetcode.com/uploads/2019/11/04/133_clone_graph_question.png)

```
Input: adjList = [[2,4],[1,3],[2,4],[1,3]]
Output: [[2,4],[1,3],[2,4],[1,3]]
Explanation: There are 4 nodes in the graph.
1st node (val = 1)'s neighbors are 2nd node (val = 2) and 4th node (val = 4).
2nd node (val = 2)'s neighbors are 1st node (val = 1) and 3rd node (val = 3).
3rd node (val = 3)'s neighbors are 2nd node (val = 2) and 4th node (val = 4).
4th node (val = 4)'s neighbors are 1st node (val = 1) and 3rd node (val = 3).

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/01/07/graph.png)

```
Input: adjList = [[]]
Output: [[]]
Explanation: Note that the input contains one empty list. The graph consists of only one node with val = 1 and it does not have any neighbors.

```

**Example 3:**

```
Input: adjList = []
Output: []
Explanation: This an empty graph, it does not have any nodes.

```

**Constraints:**

* The number of nodes in the graph is in the range `[0, 100]`.
* `1 <= Node.val <= 100`
* `Node.val` is unique for each node.
* There are no repeated edges and no self\-loops in the graph.
* The Graph is connected and all nodes can be visited starting from the given node.

</details>

<details>
<summary>Question 49 : Copy List with Random Pointer</summary>

[View Question](https://leetcode.com/problems/copy-list-with-random-pointer)

A linked list of length `n` is given such that each node contains an additional random pointer, which could point to any
node in the list, or `null`.

Construct a [**deep copy**](https://en.wikipedia.org/wiki/Object_copying#Deep_copy) of the list. The deep copy should
consist of exactly `n` **brand new** nodes, where each new node has its value set to the value of its corresponding
original node. Both the `next` and `random` pointer of the new nodes should point to new nodes in the copied list such
that the pointers in the original list and copied list represent the same list state. **None of the pointers in the new
list should point to nodes in the original list**.

For example, if there are two nodes `X` and `Y` in the original list, where `X.random --> Y`, then for the corresponding
two nodes `x` and `y` in the copied list, `x.random --> y`.

Return *the head of the copied linked list*.

The linked list is represented in the input/output as a list of `n` nodes. Each node is represented as a pair
of `[val, random_index]` where:

* `val`: an integer representing `Node.val`
* `random_index`: the index of the node (range from `0` to `n-1`) that the `random` pointer points to, or `null` if it
  does not point to any node.

Your code will **only** be given the `head` of the original linked list.

**Example 1:**

![](https://assets.leetcode.com/uploads/2019/12/18/e1.png)

```
Input: head = [[7,null],[13,0],[11,4],[10,2],[1,0]]
Output: [[7,null],[13,0],[11,4],[10,2],[1,0]]

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2019/12/18/e2.png)

```
Input: head = [[1,1],[2,1]]
Output: [[1,1],[2,1]]

```

**Example 3:**

**![](https://assets.leetcode.com/uploads/2019/12/18/e3.png)**

```
Input: head = [[3,null],[3,0],[3,null]]
Output: [[3,null],[3,0],[3,null]]

```

**Constraints:**

* `0 <= n <= 1000`
* `-104 <= Node.val <= 104`
* `Node.random` is `null` or is pointing to some node in the linked list.

</details>

<details>
<summary>Question 50 : Is Graph Bipartite</summary>

[View Question](https://leetcode.com/problems/is-graph-bipartite)

There is an **undirected** graph with `n` nodes, where each node is numbered between `0` and `n - 1`. You are given a 2D
array `graph`, where `graph[u]` is an array of nodes that node `u` is adjacent to. More formally, for each `v`
in `graph[u]`, there is an undirected edge between node `u` and node `v`. The graph has the following properties:

* There are no self\-edges (`graph[u]` does not contain `u`).
* There are no parallel edges (`graph[u]` does not contain duplicate values).
* If `v` is in `graph[u]`, then `u` is in `graph[v]` (the graph is undirected).
* The graph may not be connected, meaning there may be two nodes `u` and `v` such that there is no path between them.

A graph is **bipartite** if the nodes can be partitioned into two independent sets `A` and `B` such that **every** edge
in the graph connects a node in set `A` and a node in set `B`.

Return `true` *if and only if it is **bipartite***.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/10/21/bi2.jpg)

```
Input: graph = [[1,2,3],[0,2],[0,1,3],[0,2]]
Output: false
Explanation: There is no way to partition the nodes into two independent sets such that every edge connects a node in one and a node in the other.
```

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/10/21/bi1.jpg)

```
Input: graph = [[1,3],[0,2],[1,3],[0,2]]
Output: true
Explanation: We can partition the nodes into two sets: {0, 2} and {1, 3}.
```

**Constraints:**

* `graph.length == n`
* `1 <= n <= 100`
* `0 <= graph[u].length < n`
* `0 <= graph[u][i] <= n - 1`
* `graph[u]` does not contain `u`.
* All the values of `graph[u]` are **unique**.
* If `graph[u]` contains `v`, then `graph[v]` contains `u`.

</details>

<details>
<summary>Question 51 : Evaluate Division</summary>

[View Question](https://leetcode.com/problems/evaluate-division)

You are given an array of variable pairs `equations` and an array of real numbers `values`,
where `equations[i] = [Ai, Bi]` and `values[i]` represent the equation `Ai / Bi = values[i]`. Each `Ai` or `Bi` is a
string that represents a single variable.

You are also given some `queries`, where `queries[j] = [Cj, Dj]` represents the `jth` query where you must find the
answer for `Cj / Dj = ?`.

Return *the answers to all queries*. If a single answer cannot be determined, return `-1.0`.

**Note:** The input is always valid. You may assume that evaluating the queries will not result in division by zero and
that there is no contradiction.

**Note:**The variables that do not occur in the list of equations are undefined, so the answer cannot be determined for
them.

**Example 1:**

```
Input: equations = [["a","b"],["b","c"]], values = [2.0,3.0], queries = [["a","c"],["b","a"],["a","e"],["a","a"],["x","x"]]
Output: [6.00000,0.50000,-1.00000,1.00000,-1.00000]
Explanation: 
Given: a / b = 2.0, b / c = 3.0
queries are: a / c = ?, b / a = ?, a / e = ?, a / a = ?, x / x = ? 
return: [6.0, 0.5, -1.0, 1.0, -1.0 ]
note: x is undefined => -1.0
```

**Example 2:**

```
Input: equations = [["a","b"],["b","c"],["bc","cd"]], values = [1.5,2.5,5.0], queries = [["a","c"],["c","b"],["bc","cd"],["cd","bc"]]
Output: [3.75000,0.40000,5.00000,0.20000]

```

**Example 3:**

```
Input: equations = [["a","b"]], values = [0.5], queries = [["a","b"],["b","a"],["a","c"],["x","y"]]
Output: [0.50000,2.00000,-1.00000,-1.00000]

```

**Constraints:**

* `1 <= equations.length <= 20`
* `equations[i].length == 2`
* `1 <= Ai.length, Bi.length <= 5`
* `values.length == equations.length`
* `0.0 < values[i] <= 20.0`
* `1 <= queries.length <= 20`
* `queries[i].length == 2`
* `1 <= Cj.length, Dj.length <= 5`
* `Ai, Bi, Cj, Dj` consist of lower case English letters and digits.

</details>

<details>
<summary>Question 52 : Maximum Subarray</summary>

[View Question](https://leetcode.com/problems/maximum-subarray)

Given an integer array `nums`, find the subarray with the largest sum, and return *its sum*.

**Example 1:**

```
Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
Output: 6
Explanation: The subarray [4,-1,2,1] has the largest sum 6.

```

**Example 2:**

```
Input: nums = [1]
Output: 1
Explanation: The subarray [1] has the largest sum 1.

```

**Example 3:**

```
Input: nums = [5,4,-1,7,8]
Output: 23
Explanation: The subarray [5,4,-1,7,8] has the largest sum 23.

```

**Constraints:**

* `1 <= nums.length <= 105`
* `-104 <= nums[i] <= 104`

**Follow up:** If you have figured out the `O(n)` solution, try coding another solution using the **divide and conquer**
approach, which is more subtle.




</details>

<details>
<summary>Question 53 : Maximum Product Subarray</summary>

[View Question](https://leetcode.com/problems/maximum-product-subarray)

Given an integer array `nums`, find a subarray that has the largest product, and return *the product*.

The test cases are generated so that the answer will fit in a **32\-bit** integer.

**Example 1:**

```
Input: nums = [2,3,-2,4]
Output: 6
Explanation: [2,3] has the largest product 6.

```

**Example 2:**

```
Input: nums = [-2,0,-1]
Output: 0
Explanation: The result cannot be 2, because [-2,-1] is not a subarray.

```

**Constraints:**

* `1 <= nums.length <= 2 * 104`
* `-10 <= nums[i] <= 10`
* The product of any subarray of `nums` is **guaranteed** to fit in a **32\-bit** integer.

</details>

<details>
<summary>Question 54 : Unique Paths</summary>

[View Question](https://leetcode.com/problems/unique-paths)

There is a robot on an `m x n` grid. The robot is initially located at the **top\-left corner** (i.e., `grid[0][0]`).
The robot tries to move to the **bottom\-right corner** (i.e., `grid[m - 1][n - 1]`). The robot can only move either
down or right at any point in time.

Given the two integers `m` and `n`, return *the number of possible unique paths that the robot can take to reach the
bottom\-right corner*.

The test cases are generated so that the answer will be less than or equal to `2 * 109`.

**Example 1:**

![](https://assets.leetcode.com/uploads/2018/10/22/robot_maze.png)

```
Input: m = 3, n = 7
Output: 28

```

**Example 2:**

```
Input: m = 3, n = 2
Output: 3
Explanation: From the top-left corner, there are a total of 3 ways to reach the bottom-right corner:
1. Right -> Down -> Down
2. Down -> Down -> Right
3. Down -> Right -> Down

```

**Constraints:**

* `1 <= m, n <= 100`

</details>

<details>
<summary>Question 55 : Minimum Path Sum</summary>

[View Question](https://leetcode.com/problems/minimum-path-sum)

Given a `m x n` `grid` filled with non\-negative numbers, find a path from top left to bottom right, which minimizes the
sum of all numbers along its path.

**Note:** You can only move either down or right at any point in time.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/11/05/minpath.jpg)

```
Input: grid = [[1,3,1],[1,5,1],[4,2,1]]
Output: 7
Explanation: Because the path 1 → 3 → 1 → 1 → 1 minimizes the sum.

```

**Example 2:**

```
Input: grid = [[1,2,3],[4,5,6]]
Output: 12

```

**Constraints:**

* `m == grid.length`
* `n == grid[i].length`
* `1 <= m, n <= 200`
* `0 <= grid[i][j] <= 200`

</details>

<details>
<summary>Question 56 : Longest Substring Without Repeating Characters</summary>

[View Question](https://leetcode.com/problems/longest-substring-without-repeating-characters)

Given a string `s`, find the length of the **longest** **substring** without repeating characters.

**Example 1:**

```
Input: s = "abcabcbb"
Output: 3
Explanation: The answer is "abc", with the length of 3.

```

**Example 2:**

```
Input: s = "bbbbb"
Output: 1
Explanation: The answer is "b", with the length of 1.

```

**Example 3:**

```
Input: s = "pwwkew"
Output: 3
Explanation: The answer is "wke", with the length of 3.
Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.

```

**Constraints:**

* `0 <= s.length <= 5 * 104`
* `s` consists of English letters, digits, symbols and spaces.

</details>

<details>
<summary>Question 57 : Max Consecutive Ones III</summary>

[View Question](https://leetcode.com/problems/max-consecutive-ones-iii)

Given a binary array `nums` and an integer `k`, return *the maximum number of consecutive* `1`*'s in the array if you
can flip at most* `k` `0`'s.

**Example 1:**

```
Input: nums = [1,1,1,0,0,0,1,1,1,1,0], k = 2
Output: 6
Explanation: [1,1,1,0,0,1,1,1,1,1,1]
Bolded numbers were flipped from 0 to 1. The longest subarray is underlined.
```

**Example 2:**

```
Input: nums = [0,0,1,1,0,0,1,1,1,0,1,1,0,0,0,1,1,1,1], k = 3
Output: 10
Explanation: [0,0,1,1,1,1,1,1,1,1,1,1,0,0,0,1,1,1,1]
Bolded numbers were flipped from 0 to 1. The longest subarray is underlined.

```

**Constraints:**

* `1 <= nums.length <= 105`
* `nums[i]` is either `0` or `1`.
* `0 <= k <= nums.length`

</details>

<details>
<summary>Question 58 : Maximize the Confusion of An Exam</summary>

[View Question](https://leetcode.com/problems/maximize-the-confusion-of-an-exam)

A teacher is writing a test with `n` true/false questions, with `'T'` denoting true and `'F'` denoting false. He wants
to confuse the students by **maximizing** the number of **consecutive** questions with the **same** answer (multiple
trues or multiple falses in a row).

You are given a string `answerKey`, where `answerKey[i]` is the original answer to the `ith` question. In addition, you
are given an integer `k`, the maximum number of times you may perform the following operation:

* Change the answer key for any question to `'T'` or `'F'` (i.e., set `answerKey[i]` to `'T'` or `'F'`).

Return *the **maximum** number of consecutive* `'T'`s or `'F'`s *in the answer key after performing the operation at
most* `k` *times*.

**Example 1:**

```
Input: answerKey = "TTFF", k = 2
Output: 4
Explanation: We can replace both the 'F's with 'T's to make answerKey = "TTTT".
There are four consecutive 'T's.

```

**Example 2:**

```
Input: answerKey = "TFFT", k = 1
Output: 3
Explanation: We can replace the first 'T' with an 'F' to make answerKey = "FFFT".
Alternatively, we can replace the second 'T' with an 'F' to make answerKey = "TFFF".
In both cases, there are three consecutive 'F's.

```

**Example 3:**

```
Input: answerKey = "TTFTTFTT", k = 1
Output: 5
Explanation: We can replace the first 'F' to make answerKey = "TTTTTFTT"
Alternatively, we can replace the second 'F' to make answerKey = "TTFTTTTT". 
In both cases, there are five consecutive 'T's.

```

**Constraints:**

* `n == answerKey.length`
* `1 <= n <= 5 * 104`
* `answerKey[i]` is either `'T'` or `'F'`
* `1 <= k <= n`

</details>

<details>
<summary>Question 59 : Longest Nice Subarray</summary>

[View Question](https://leetcode.com/problems/longest-nice-subarray)

You are given an array `nums` consisting of **positive** integers.

We call a subarray of `nums` **nice** if the bitwise **AND** of every pair of elements that are in **different**
positions in the subarray is equal to `0`.

Return *the length of the **longest** nice subarray*.

A **subarray** is a **contiguous** part of an array.

**Note** that subarrays of length `1` are always considered nice.

**Example 1:**

```
Input: nums = [1,3,8,48,10]
Output: 3
Explanation: The longest nice subarray is [3,8,48]. This subarray satisfies the conditions:
- 3 AND 8 = 0.
- 3 AND 48 = 0.
- 8 AND 48 = 0.
It can be proven that no longer nice subarray can be obtained, so we return 3.
```

**Example 2:**

```
Input: nums = [3,1,5,11,13]
Output: 1
Explanation: The length of the longest nice subarray is 1. Any subarray of length 1 can be chosen.

```

**Constraints:**

* `1 <= nums.length <= 105`
* `1 <= nums[i] <= 109`

</details>

<details>
<summary>Question 60 : Random Pick with Weight</summary>

[View Question](https://leetcode.com/problems/random-pick-with-weight)

You are given a **0\-indexed** array of positive integers `w` where `w[i]` describes the **weight** of the `ith` index.

You need to implement the function `pickIndex()`, which **randomly** picks an index in the range `[0, w.length - 1]` (*
*inclusive**) and returns it. The **probability** of picking an index `i` is `w[i] / sum(w)`.

* For example, if `w = [1, 3]`, the probability of picking index `0` is `1 / (1 + 3) = 0.25` (i.e., `25%`), and the
  probability of picking index `1` is `3 / (1 + 3) = 0.75` (i.e., `75%`).

**Example 1:**

```
Input
["Solution","pickIndex"]
[[[1]],[]]
Output
[null,0]

Explanation
Solution solution = new Solution([1]);
solution.pickIndex(); // return 0. The only option is to return 0 since there is only one element in w.

```

**Example 2:**

```
Input
["Solution","pickIndex","pickIndex","pickIndex","pickIndex","pickIndex"]
[[[1,3]],[],[],[],[],[]]
Output
[null,1,1,1,1,0]

Explanation
Solution solution = new Solution([1, 3]);
solution.pickIndex(); // return 1. It is returning the second element (index = 1) that has a probability of 3/4.
solution.pickIndex(); // return 1
solution.pickIndex(); // return 1
solution.pickIndex(); // return 1
solution.pickIndex(); // return 0. It is returning the first element (index = 0) that has a probability of 1/4.

Since this is a randomization problem, multiple answers are allowed.
All of the following outputs can be considered correct:
[null,1,1,1,1,0]
[null,1,1,1,1,1]
[null,1,1,1,0,0]
[null,1,1,1,0,1]
[null,1,0,1,0,0]
......
and so on.

```

**Constraints:**

* `1 <= w.length <= 104`
* `1 <= w[i] <= 105`
* `pickIndex` will be called at most `104` times.

</details>

<details>
<summary>Question 61 : Word Break</summary>

[View Question](https://leetcode.com/problems/word-break)

Given a string `s` and a dictionary of strings `wordDict`, return `true` if `s` can be segmented into a space\-separated
sequence of one or more dictionary words.

**Note** that the same word in the dictionary may be reused multiple times in the segmentation.

**Example 1:**

```
Input: s = "leetcode", wordDict = ["leet","code"]
Output: true
Explanation: Return true because "leetcode" can be segmented as "leet code".

```

**Example 2:**

```
Input: s = "applepenapple", wordDict = ["apple","pen"]
Output: true
Explanation: Return true because "applepenapple" can be segmented as "apple pen apple".
Note that you are allowed to reuse a dictionary word.

```

**Example 3:**

```
Input: s = "catsandog", wordDict = ["cats","dog","sand","and","cat"]
Output: false

```

**Constraints:**

* `1 <= s.length <= 300`
* `1 <= wordDict.length <= 1000`
* `1 <= wordDict[i].length <= 20`
* `s` and `wordDict[i]` consist of only lowercase English letters.
* All the strings of `wordDict` are **unique**.

</details>

<details>
<summary>Question 62 : House Robber</summary>

[View Question](https://leetcode.com/problems/house-robber)

You are a professional robber planning to rob houses along a street. Each house has a certain amount of money stashed,
the only constraint stopping you from robbing each of them is that adjacent houses have security systems connected and *
*it will automatically contact the police if two adjacent houses were broken into on the same night**.

Given an integer array `nums` representing the amount of money of each house, return *the maximum amount of money you
can rob tonight **without alerting the police***.

**Example 1:**

```
Input: nums = [1,2,3,1]
Output: 4
Explanation: Rob house 1 (money = 1) and then rob house 3 (money = 3).
Total amount you can rob = 1 + 3 = 4.

```

**Example 2:**

```
Input: nums = [2,7,9,3,1]
Output: 12
Explanation: Rob house 1 (money = 2), rob house 3 (money = 9) and rob house 5 (money = 1).
Total amount you can rob = 2 + 9 + 1 = 12.

```

**Constraints:**

* `1 <= nums.length <= 100`
* `0 <= nums[i] <= 400`

</details>

<details>
<summary>Question 63 : Coin Change</summary>

[View Question](https://leetcode.com/problems/coin-change)

You are given an integer array `coins` representing coins of different denominations and an integer `amount`
representing a total amount of money.

Return *the fewest number of coins that you need to make up that amount*. If that amount of money cannot be made up by
any combination of the coins, return `-1`.

You may assume that you have an infinite number of each kind of coin.

**Example 1:**

```
Input: coins = [1,2,5], amount = 11
Output: 3
Explanation: 11 = 5 + 5 + 1

```

**Example 2:**

```
Input: coins = [2], amount = 3
Output: -1

```

**Example 3:**

```
Input: coins = [1], amount = 0
Output: 0

```

**Constraints:**

* `1 <= coins.length <= 12`
* `1 <= coins[i] <= 231 - 1`
* `0 <= amount <= 104`

</details>

<details>
<summary>Question 64 : Longest Increasing Subsequence</summary>

[View Question](https://leetcode.com/problems/longest-increasing-subsequence)

Given an integer array `nums`, return *the length of the longest **strictly increasing*** ***subsequence***.

**Example 1:**

```
Input: nums = [10,9,2,5,3,7,101,18]
Output: 4
Explanation: The longest increasing subsequence is [2,3,7,101], therefore the length is 4.

```

**Example 2:**

```
Input: nums = [0,1,0,3,2,3]
Output: 4

```

**Example 3:**

```
Input: nums = [7,7,7,7,7,7,7]
Output: 1

```

**Constraints:**

* `1 <= nums.length <= 2500`
* `-104 <= nums[i] <= 104`

**Follow up:** Can you come up with an algorithm that runs in `O(n log(n))` time complexity?




</details>

<details>
<summary>Question 65 : Longest Common Subsequence</summary>

[View Question](https://leetcode.com/problems/longest-common-subsequence)

Given two strings `text1` and `text2`, return *the length of their longest **common subsequence**.* If there is no *
*common subsequence**, return `0`.

A **subsequence** of a string is a new string generated from the original string with some characters (can be none)
deleted without changing the relative order of the remaining characters.

* For example, `"ace"` is a subsequence of `"abcde"`.

A **common subsequence** of two strings is a subsequence that is common to both strings.

**Example 1:**

```
Input: text1 = "abcde", text2 = "ace" 
Output: 3  
Explanation: The longest common subsequence is "ace" and its length is 3.

```

**Example 2:**

```
Input: text1 = "abc", text2 = "abc"
Output: 3
Explanation: The longest common subsequence is "abc" and its length is 3.

```

**Example 3:**

```
Input: text1 = "abc", text2 = "def"
Output: 0
Explanation: There is no such common subsequence, so the result is 0.

```

**Constraints:**

* `1 <= text1.length, text2.length <= 1000`
* `text1` and `text2` consist of only lowercase English characters.

</details>

<details>
<summary>Question 66 : Lowest Common Ancestor of a Binary Search Tree</summary>

[View Question](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree)

Given a binary search tree (BST), find the lowest common ancestor (LCA) node of two given nodes in the BST.

According to the [definition of LCA on Wikipedia](https://en.wikipedia.org/wiki/Lowest_common_ancestor): “The lowest
common ancestor is defined between two nodes `p` and `q` as the lowest node in `T` that has both `p` and `q` as
descendants (where we allow **a node to be a descendant of itself**).”

**Example 1:**

![](https://assets.leetcode.com/uploads/2018/12/14/binarysearchtree_improved.png)

```
Input: root = [6,2,8,0,4,7,9,null,null,3,5], p = 2, q = 8
Output: 6
Explanation: The LCA of nodes 2 and 8 is 6.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2018/12/14/binarysearchtree_improved.png)

```
Input: root = [6,2,8,0,4,7,9,null,null,3,5], p = 2, q = 4
Output: 2
Explanation: The LCA of nodes 2 and 4 is 2, since a node can be a descendant of itself according to the LCA definition.

```

**Example 3:**

```
Input: root = [2,1], p = 2, q = 1
Output: 2

```

**Constraints:**

* The number of nodes in the tree is in the range `[2, 105]`.
* `-109 <= Node.val <= 109`
* All `Node.val` are **unique**.
* `p != q`
* `p` and `q` will exist in the BST.

</details>

<details>
<summary>Question 67 : Binary Tree Maximum Path Sum</summary>

[View Question](https://leetcode.com/problems/binary-tree-maximum-path-sum)

A **path** in a binary tree is a sequence of nodes where each pair of adjacent nodes in the sequence has an edge
connecting them. A node can only appear in the sequence **at most once**. Note that the path does not need to pass
through the root.

The **path sum** of a path is the sum of the node's values in the path.

Given the `root` of a binary tree, return *the maximum **path sum** of any **non\-empty** path*.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/10/13/exx1.jpg)

```
Input: root = [1,2,3]
Output: 6
Explanation: The optimal path is 2 -> 1 -> 3 with a path sum of 2 + 1 + 3 = 6.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/10/13/exx2.jpg)

```
Input: root = [-10,9,20,null,null,15,7]
Output: 42
Explanation: The optimal path is 15 -> 20 -> 7 with a path sum of 15 + 20 + 7 = 42.

```

**Constraints:**

* The number of nodes in the tree is in the range `[1, 3 * 104]`.
* `-1000 <= Node.val <= 1000`

</details>

<details>
<summary>Question 68 : Best Time to Buy and Sell Stock II</summary>

[View Question](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii)

You are given an integer array `prices` where `prices[i]` is the price of a given stock on the `ith` day.

On each day, you may decide to buy and/or sell the stock. You can only hold **at most one** share of the stock at any
time. However, you can buy it then immediately sell it on the **same day**.

Find and return *the **maximum** profit you can achieve*.

**Example 1:**

```
Input: prices = [7,1,5,3,6,4]
Output: 7
Explanation: Buy on day 2 (price = 1) and sell on day 3 (price = 5), profit = 5-1 = 4.
Then buy on day 4 (price = 3) and sell on day 5 (price = 6), profit = 6-3 = 3.
Total profit is 4 + 3 = 7.

```

**Example 2:**

```
Input: prices = [1,2,3,4,5]
Output: 4
Explanation: Buy on day 1 (price = 1) and sell on day 5 (price = 5), profit = 5-1 = 4.
Total profit is 4.

```

**Example 3:**

```
Input: prices = [7,6,4,3,1]
Output: 0
Explanation: There is no way to make a positive profit, so we never buy the stock to achieve the maximum profit of 0.

```

**Constraints:**

* `1 <= prices.length <= 3 * 104`
* `0 <= prices[i] <= 104`

</details>

<details>
<summary>Question 69 : Jump Game</summary>

[View Question](https://leetcode.com/problems/jump-game)

You are given an integer array `nums`. You are initially positioned at the array's **first index**, and each element in
the array represents your maximum jump length at that position.

Return `true` *if you can reach the last index, or* `false` *otherwise*.

**Example 1:**

```
Input: nums = [2,3,1,1,4]
Output: true
Explanation: Jump 1 step from index 0 to 1, then 3 steps to the last index.

```

**Example 2:**

```
Input: nums = [3,2,1,0,4]
Output: false
Explanation: You will always arrive at index 3 no matter what. Its maximum jump length is 0, which makes it impossible to reach the last index.

```

**Constraints:**

* `1 <= nums.length <= 104`
* `0 <= nums[i] <= 105`

</details>

<details>
<summary>Question 70 : Course Schedule II</summary>

[View Question](https://leetcode.com/problems/course-schedule-ii)

There are a total of `numCourses` courses you have to take, labeled from `0` to `numCourses - 1`. You are given an
array `prerequisites` where `prerequisites[i] = [ai, bi]` indicates that you **must** take course `bi` first if you want
to take course `ai`.

* For example, the pair `[0, 1]`, indicates that to take course `0` you have to first take course `1`.

Return *the ordering of courses you should take to finish all courses*. If there are many valid answers, return **any**
of them. If it is impossible to finish all courses, return **an empty array**.

**Example 1:**

```
Input: numCourses = 2, prerequisites = [[1,0]]
Output: [0,1]
Explanation: There are a total of 2 courses to take. To take course 1 you should have finished course 0. So the correct course order is [0,1].

```

**Example 2:**

```
Input: numCourses = 4, prerequisites = [[1,0],[2,0],[3,1],[3,2]]
Output: [0,2,1,3]
Explanation: There are a total of 4 courses to take. To take course 3 you should have finished both courses 1 and 2. Both courses 1 and 2 should be taken after you finished course 0.
So one correct course order is [0,1,2,3]. Another correct ordering is [0,2,1,3].

```

**Example 3:**

```
Input: numCourses = 1, prerequisites = []
Output: [0]

```

**Constraints:**

* `1 <= numCourses <= 2000`
* `0 <= prerequisites.length <= numCourses * (numCourses - 1)`
* `prerequisites[i].length == 2`
* `0 <= ai, bi < numCourses`
* `ai != bi`
* All the pairs `[ai, bi]` are **distinct**.

</details>

<details>
<summary>Question 71 : Path with Maximum Probability</summary>

[View Question](https://leetcode.com/problems/path-with-maximum-probability)

You are given an undirected weighted graph of `n` nodes (0\-indexed), represented by an edge list
where `edges[i] = [a, b]` is an undirected edge connecting the nodes `a` and `b` with a probability of success of
traversing that edge `succProb[i]`.

Given two nodes `start` and `end`, find the path with the maximum probability of success to go from `start` to `end` and
return its success probability.

If there is no path from `start` to `end`, **return 0**. Your answer will be accepted if it differs from the correct
answer by at most **1e\-5**.

**Example 1:**

**![](https://assets.leetcode.com/uploads/2019/09/20/1558_ex1.png)**

```
Input: n = 3, edges = [[0,1],[1,2],[0,2]], succProb = [0.5,0.5,0.2], start = 0, end = 2
Output: 0.25000
Explanation: There are two paths from start to end, one having a probability of success = 0.2 and the other has 0.5 * 0.5 = 0.25.

```

**Example 2:**

**![](https://assets.leetcode.com/uploads/2019/09/20/1558_ex2.png)**

```
Input: n = 3, edges = [[0,1],[1,2],[0,2]], succProb = [0.5,0.5,0.3], start = 0, end = 2
Output: 0.30000

```

**Example 3:**

**![](https://assets.leetcode.com/uploads/2019/09/20/1558_ex3.png)**

```
Input: n = 3, edges = [[0,1]], succProb = [0.5], start = 0, end = 2
Output: 0.00000
Explanation: There is no path between 0 and 2.

```

**Constraints:**

* `2 <= n <= 10^4`
* `0 <= start, end < n`
* `start != end`
* `0 <= a, b < n`
* `a != b`
* `0 <= succProb.length == edges.length <= 2*10^4`
* `0 <= succProb[i] <= 1`
* There is at most one edge between every two nodes.

</details>

<details>
<summary>Question 72 : Path With Minimum Effort</summary>

[View Question](https://leetcode.com/problems/path-with-minimum-effort)

You are a hiker preparing for an upcoming hike. You are given `heights`, a 2D array of size `rows x columns`,
where `heights[row][col]` represents the height of cell `(row, col)`. You are situated in the top\-left cell, `(0, 0)`,
and you hope to travel to the bottom\-right cell, `(rows-1, columns-1)` (i.e., **0\-indexed**). You can move **up**, *
*down**, **left**, or **right**, and you wish to find a route that requires the minimum **effort**.

A route's **effort** is the **maximum absolute difference**in heights between two consecutive cells of the route.

Return *the minimum **effort** required to travel from the top\-left cell to the bottom\-right cell.*

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/10/04/ex1.png)

```
Input: heights = [[1,2,2],[3,8,2],[5,3,5]]
Output: 2
Explanation: The route of [1,3,5,3,5] has a maximum absolute difference of 2 in consecutive cells.
This is better than the route of [1,2,2,2,5], where the maximum absolute difference is 3.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/10/04/ex2.png)

```
Input: heights = [[1,2,3],[3,8,4],[5,3,5]]
Output: 1
Explanation: The route of [1,2,3,4,5] has a maximum absolute difference of 1 in consecutive cells, which is better than route [1,3,5,3,5].

```

**Example 3:**

![](https://assets.leetcode.com/uploads/2020/10/04/ex3.png)

```
Input: heights = [[1,2,1,1,1],[1,2,1,2,1],[1,2,1,2,1],[1,2,1,2,1],[1,1,1,2,1]]
Output: 0
Explanation: This route does not require any effort.

```

**Constraints:**

* `rows == heights.length`
* `columns == heights[i].length`
* `1 <= rows, columns <= 100`
* `1 <= heights[i][j] <= 106`

</details>

<details>
<summary>Question 73 : Merge Intervals</summary>

[View Question](https://leetcode.com/problems/merge-intervals)

Given an array of `intervals` where `intervals[i] = [starti, endi]`, merge all overlapping intervals, and return *an
array of the non\-overlapping intervals that cover all the intervals in the input*.

**Example 1:**

```
Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]
Explanation: Since intervals [1,3] and [2,6] overlap, merge them into [1,6].

```

**Example 2:**

```
Input: intervals = [[1,4],[4,5]]
Output: [[1,5]]
Explanation: Intervals [1,4] and [4,5] are considered overlapping.

```

**Constraints:**

* `1 <= intervals.length <= 104`
* `intervals[i].length == 2`
* `0 <= starti <= endi <= 104`

</details>

<details>
<summary>Question 74 : Insert Interval</summary>

[View Question](https://leetcode.com/problems/insert-interval)

You are given an array of non\-overlapping intervals `intervals` where `intervals[i] = [starti, endi]` represent the
start and the end of the `ith` interval and `intervals` is sorted in ascending order by `starti`. You are also given an
interval `newInterval = [start, end]` that represents the start and end of another interval.

Insert `newInterval` into `intervals` such that `intervals` is still sorted in ascending order by `starti`
and `intervals` still does not have any overlapping intervals (merge overlapping intervals if necessary).

Return `intervals` *after the insertion*.

**Note** that you don't need to modify `intervals` in\-place. You can make a new array and return it.

**Example 1:**

```
Input: intervals = [[1,3],[6,9]], newInterval = [2,5]
Output: [[1,5],[6,9]]

```

**Example 2:**

```
Input: intervals = [[1,2],[3,5],[6,7],[8,10],[12,16]], newInterval = [4,8]
Output: [[1,2],[3,10],[12,16]]
Explanation: Because the new interval [4,8] overlaps with [3,5],[6,7],[8,10].

```

**Constraints:**

* `0 <= intervals.length <= 104`
* `intervals[i].length == 2`
* `0 <= starti <= endi <= 105`
* `intervals` is sorted by `starti` in **ascending** order.
* `newInterval.length == 2`
* `0 <= start <= end <= 105`

</details>

<details>
<summary>Question 75 : Interval List Intersections</summary>

[View Question](https://leetcode.com/problems/interval-list-intersections)

You are given two lists of closed intervals, `firstList` and `secondList`, where `firstList[i] = [starti, endi]`
and `secondList[j] = [startj, endj]`. Each list of intervals is pairwise **disjoint** and in **sorted order**.

Return *the intersection of these two interval lists*.

A **closed interval** `[a, b]` (with `a <= b`) denotes the set of real numbers `x` with `a <= x <= b`.

The **intersection** of two closed intervals is a set of real numbers that are either empty or represented as a closed
interval. For example, the intersection of `[1, 3]` and `[2, 4]` is `[2, 3]`.

**Example 1:**

![](https://assets.leetcode.com/uploads/2019/01/30/interval1.png)

```
Input: firstList = [[0,2],[5,10],[13,23],[24,25]], secondList = [[1,5],[8,12],[15,24],[25,26]]
Output: [[1,2],[5,5],[8,10],[15,23],[24,24],[25,25]]

```

**Example 2:**

```
Input: firstList = [[1,3],[5,9]], secondList = []
Output: []

```

**Constraints:**

* `0 <= firstList.length, secondList.length <= 1000`
* `firstList.length + secondList.length >= 1`
* `0 <= starti < endi <= 109`
* `endi < starti+1`
* `0 <= startj < endj <= 109`
* `endj < startj+1`

</details>

<details>
<summary>Question 76 : LRU Cache</summary>

[View Question](https://leetcode.com/problems/lru-cache)

Design a data structure that follows the constraints of a *
*[Least Recently Used (LRU) cache](https://en.wikipedia.org/wiki/Cache_replacement_policies#LRU)**.

Implement the `LRUCache` class:

* `LRUCache(int capacity)` Initialize the LRU cache with **positive** size `capacity`.
* `int get(int key)` Return the value of the `key` if the key exists, otherwise return `-1`.
* `void put(int key, int value)` Update the value of the `key` if the `key` exists. Otherwise, add the `key-value` pair
  to the cache. If the number of keys exceeds the `capacity` from this operation, **evict** the least recently used key.

The functions `get` and `put` must each run in `O(1)` average time complexity.

**Example 1:**

```
Input
["LRUCache", "put", "put", "get", "put", "get", "put", "get", "get", "get"]
[[2], [1, 1], [2, 2], [1], [3, 3], [2], [4, 4], [1], [3], [4]]
Output
[null, null, null, 1, null, -1, null, -1, 3, 4]

Explanation
LRUCache lRUCache = new LRUCache(2);
lRUCache.put(1, 1); // cache is {1=1}
lRUCache.put(2, 2); // cache is {1=1, 2=2}
lRUCache.get(1);    // return 1
lRUCache.put(3, 3); // LRU key was 2, evicts key 2, cache is {1=1, 3=3}
lRUCache.get(2);    // returns -1 (not found)
lRUCache.put(4, 4); // LRU key was 1, evicts key 1, cache is {4=4, 3=3}
lRUCache.get(1);    // return -1 (not found)
lRUCache.get(3);    // return 3
lRUCache.get(4);    // return 4

```

**Constraints:**

* `1 <= capacity <= 3000`
* `0 <= key <= 104`
* `0 <= value <= 105`
* At most `2 * 105` calls will be made to `get` and `put`.

</details>

<details>
<summary>Question 77 : Binary Search Tree Iterator</summary>

[View Question](https://leetcode.com/problems/binary-search-tree-iterator)

Implement the `BSTIterator` class that represents an iterator over the *
*[in\-order traversal](https://en.wikipedia.org/wiki/Tree_traversal#In-order_(LNR))** of a binary search tree (BST):

* `BSTIterator(TreeNode root)` Initializes an object of the `BSTIterator` class. The `root` of the BST is given as part
  of the constructor. The pointer should be initialized to a non\-existent number smaller than any element in the BST.
* `boolean hasNext()` Returns `true` if there exists a number in the traversal to the right of the pointer, otherwise
  returns `false`.
* `int next()` Moves the pointer to the right, then returns the number at the pointer.

Notice that by initializing the pointer to a non\-existent smallest number, the first call to `next()` will return the
smallest element in the BST.

You may assume that `next()` calls will always be valid. That is, there will be at least a next number in the in\-order
traversal when `next()` is called.

**Example 1:**

![](https://assets.leetcode.com/uploads/2018/12/25/bst-tree.png)

```
Input
["BSTIterator", "next", "next", "hasNext", "next", "hasNext", "next", "hasNext", "next", "hasNext"]
[[[7, 3, 15, null, null, 9, 20]], [], [], [], [], [], [], [], [], []]
Output
[null, 3, 7, true, 9, true, 15, true, 20, false]

Explanation
BSTIterator bSTIterator = new BSTIterator([7, 3, 15, null, null, 9, 20]);
bSTIterator.next();    // return 3
bSTIterator.next();    // return 7
bSTIterator.hasNext(); // return True
bSTIterator.next();    // return 9
bSTIterator.hasNext(); // return True
bSTIterator.next();    // return 15
bSTIterator.hasNext(); // return True
bSTIterator.next();    // return 20
bSTIterator.hasNext(); // return False

```

**Constraints:**

* The number of nodes in the tree is in the range `[1, 105]`.
* `0 <= Node.val <= 106`
* At most `105` calls will be made to `hasNext`, and `next`.

**Follow up:**

* Could you implement `next()` and `hasNext()` to run in average `O(1)` time and use `O(h)` memory, where `h` is the
  height of the tree?

</details>

<details>
<summary>Question 78 : Min Stack</summary>

[View Question](https://leetcode.com/problems/min-stack)

Design a stack that supports push, pop, top, and retrieving the minimum element in constant time.

Implement the `MinStack` class:

* `MinStack()` initializes the stack object.
* `void push(int val)` pushes the element `val` onto the stack.
* `void pop()` removes the element on the top of the stack.
* `int top()` gets the top element of the stack.
* `int getMin()` retrieves the minimum element in the stack.

You must implement a solution with `O(1)` time complexity for each function.

**Example 1:**

```
Input
["MinStack","push","push","push","getMin","pop","top","getMin"]
[[],[-2],[0],[-3],[],[],[],[]]

Output
[null,null,null,null,-3,null,0,-2]

Explanation
MinStack minStack = new MinStack();
minStack.push(-2);
minStack.push(0);
minStack.push(-3);
minStack.getMin(); // return -3
minStack.pop();
minStack.top();    // return 0
minStack.getMin(); // return -2

```

**Constraints:**

* `-231 <= val <= 231 - 1`
* Methods `pop`, `top` and `getMin` operations will always be called on **non\-empty** stacks.
* At most `3 * 104` calls will be made to `push`, `pop`, `top`, and `getMin`.

</details>

<details>
<summary>Question 79 : Implement Stack using Queues</summary>

[View Question](https://leetcode.com/problems/implement-stack-using-queues)

Implement a last\-in\-first\-out (LIFO) stack using only two queues. The implemented stack should support all the
functions of a normal stack (`push`, `top`, `pop`, and `empty`).

Implement the `MyStack` class:

* `void push(int x)` Pushes element x to the top of the stack.
* `int pop()` Removes the element on the top of the stack and returns it.
* `int top()` Returns the element on the top of the stack.
* `boolean empty()` Returns `true` if the stack is empty, `false` otherwise.

**Notes:**

* You must use **only** standard operations of a queue, which means that
  only `push to back`, `peek/pop from front`, `size` and `is empty` operations are valid.
* Depending on your language, the queue may not be supported natively. You may simulate a queue using a list or deque (
  double\-ended queue) as long as you use only a queue's standard operations.

**Example 1:**

```
Input
["MyStack", "push", "push", "top", "pop", "empty"]
[[], [1], [2], [], [], []]
Output
[null, null, null, 2, 2, false]

Explanation
MyStack myStack = new MyStack();
myStack.push(1);
myStack.push(2);
myStack.top(); // return 2
myStack.pop(); // return 2
myStack.empty(); // return False

```

**Constraints:**

* `1 <= x <= 9`
* At most `100` calls will be made to `push`, `pop`, `top`, and `empty`.
* All the calls to `pop` and `top` are valid.

**Follow\-up:** Can you implement the stack using only one queue?




</details>

<details>
<summary>Question 80 : Letter Combinations of a Phone Number</summary>

[View Question](https://leetcode.com/problems/letter-combinations-of-a-phone-number)

Given a string containing digits from `2-9` inclusive, return all possible letter combinations that the number could
represent. Return the answer in **any order**.

A mapping of digits to letters (just like on the telephone buttons) is given below. Note that 1 does not map to any
letters.

![](https://assets.leetcode.com/uploads/2022/03/15/1200px-telephone-keypad2svg.png)

**Example 1:**

```
Input: digits = "23"
Output: ["ad","ae","af","bd","be","bf","cd","ce","cf"]

```

**Example 2:**

```
Input: digits = ""
Output: []

```

**Example 3:**

```
Input: digits = "2"
Output: ["a","b","c"]

```

**Constraints:**

* `0 <= digits.length <= 4`
* `digits[i]` is a digit in the range `['2', '9']`.

</details>

<details>
<summary>Question 81 : Combination Sum</summary>

[View Question](https://leetcode.com/problems/combination-sum)

Given an array of **distinct** integers `candidates` and a target integer `target`, return *a list of
all **unique combinations** of* `candidates` *where the chosen numbers sum to* `target`*.* You may return the
combinations in **any order**.

The **same** number may be chosen from `candidates` an **unlimited number of times**. Two combinations are unique if the
frequency of at least one of the chosen numbers is different.

The test cases are generated such that the number of unique combinations that sum up to `target` is less than `150`
combinations for the given input.

**Example 1:**

```
Input: candidates = [2,3,6,7], target = 7
Output: [[2,2,3],[7]]
Explanation:
2 and 3 are candidates, and 2 + 2 + 3 = 7. Note that 2 can be used multiple times.
7 is a candidate, and 7 = 7.
These are the only two combinations.

```

**Example 2:**

```
Input: candidates = [2,3,5], target = 8
Output: [[2,2,2,2],[2,3,3],[3,5]]

```

**Example 3:**

```
Input: candidates = [2], target = 1
Output: []

```

**Constraints:**

* `1 <= candidates.length <= 30`
* `2 <= candidates[i] <= 40`
* All elements of `candidates` are **distinct**.
* `1 <= target <= 40`

</details>

<details>
<summary>Question 82 : Permutations</summary>

[View Question](https://leetcode.com/problems/permutations)

Given an array `nums` of distinct integers, return *all the possible permutations*. You can return the answer in **any
order**.

**Example 1:**

```
Input: nums = [1,2,3]
Output: [[1,2,3],[1,3,2],[2,1,3],[2,3,1],[3,1,2],[3,2,1]]

```

**Example 2:**

```
Input: nums = [0,1]
Output: [[0,1],[1,0]]

```

**Example 3:**

```
Input: nums = [1]
Output: [[1]]

```

**Constraints:**

* `1 <= nums.length <= 6`
* `-10 <= nums[i] <= 10`
* All the integers of `nums` are **unique**.

</details>

<details>
<summary>Question 83 : Subsets</summary>

[View Question](https://leetcode.com/problems/subsets)

Given an integer array `nums` of **unique** elements, return *all possible* *subsets* *(the power set)*.

The solution set **must not** contain duplicate subsets. Return the solution in **any order**.

**Example 1:**

```
Input: nums = [1,2,3]
Output: [[],[1],[2],[1,2],[3],[1,3],[2,3],[1,2,3]]

```

**Example 2:**

```
Input: nums = [0]
Output: [[],[0]]

```

**Constraints:**

* `1 <= nums.length <= 10`
* `-10 <= nums[i] <= 10`
* All the numbers of `nums` are **unique**.

</details>

<details>
<summary>Question 84 : Palindrome Partitioning</summary>

[View Question](https://leetcode.com/problems/palindrome-partitioning)

Given a string `s`, partition `s` such that every substring of the partition is a **palindrome**. Return *all possible
palindrome partitioning of* `s`.

**Example 1:**

```
Input: s = "aab"
Output: [["a","a","b"],["aa","b"]]

```

**Example 2:**

```
Input: s = "a"
Output: [["a"]]

```

**Constraints:**

* `1 <= s.length <= 16`
* `s` contains only lowercase English letters.

</details>

<details>
<summary>Question 85 : Implement Trie (Prefix Tree)</summary>

[View Question](https://leetcode.com/problems/implement-trie-prefix-tree)

A [**trie**](https://en.wikipedia.org/wiki/Trie) (pronounced as "try") or **prefix tree** is a tree data structure used
to efficiently store and retrieve keys in a dataset of strings. There are various applications of this data structure,
such as autocomplete and spellchecker.

Implement the Trie class:

* `Trie()` Initializes the trie object.
* `void insert(String word)` Inserts the string `word` into the trie.
* `boolean search(String word)` Returns `true` if the string `word` is in the trie (i.e., was inserted before),
  and `false` otherwise.
* `boolean startsWith(String prefix)` Returns `true` if there is a previously inserted string `word` that has the
  prefix `prefix`, and `false` otherwise.

**Example 1:**

```
Input
["Trie", "insert", "search", "search", "startsWith", "insert", "search"]
[[], ["apple"], ["apple"], ["app"], ["app"], ["app"], ["app"]]
Output
[null, null, true, false, true, null, true]

Explanation
Trie trie = new Trie();
trie.insert("apple");
trie.search("apple");   // return True
trie.search("app");     // return False
trie.startsWith("app"); // return True
trie.insert("app");
trie.search("app");     // return True

```

**Constraints:**

* `1 <= word.length, prefix.length <= 2000`
* `word` and `prefix` consist only of lowercase English letters.
* At most `3 * 104` calls **in total** will be made to `insert`, `search`, and `startsWith`.

</details>

<details>
<summary>Question 86 : Basic Calculator</summary>

[View Question](https://leetcode.com/problems/basic-calculator)

Given a string `s` representing a valid expression, implement a basic calculator to evaluate it, and return *the result
of the evaluation*.

**Note:** You are **not** allowed to use any built\-in function which evaluates strings as mathematical expressions,
such as `eval()`.

**Example 1:**

```
Input: s = "1 + 1"
Output: 2

```

**Example 2:**

```
Input: s = " 2-1 + 2 "
Output: 3

```

**Example 3:**

```
Input: s = "(1+(4+5+2)-3)+(6+8)"
Output: 23

```

**Constraints:**

* `1 <= s.length <= 3 * 105`
* `s` consists of digits, `'+'`, `'-'`, `'('`, `')'`, and `' '`.
* `s` represents a valid expression.
* `'+'` is **not** used as a unary operation (i.e., `"+1"` and `"+(2 + 3)"` is invalid).
* `'-'` could be used as a unary operation (i.e., `"-1"` and `"-(2 + 3)"` is valid).
* There will be no two consecutive operators in the input.
* Every number and running calculation will fit in a signed 32\-bit integer.

</details>

<details>
<summary>Question 87 : Daily Temperatures</summary>

[View Question](https://leetcode.com/problems/daily-temperatures)

Given an array of integers `temperatures` represents the daily temperatures, return *an array* `answer` *such
that* `answer[i]` *is the number of days you have to wait after the* `ith` *day to get a warmer temperature*. If there
is no future day for which this is possible, keep `answer[i] == 0` instead.

**Example 1:**

```
Input: temperatures = [73,74,75,71,69,72,76,73]
Output: [1,1,4,2,1,1,0,0]

```

**Example 2:**

```
Input: temperatures = [30,40,50,60]
Output: [1,1,1,0]

```

**Example 3:**

```
Input: temperatures = [30,60,90]
Output: [1,1,0]

```

**Constraints:**

* `1 <= temperatures.length <= 105`
* `30 <= temperatures[i] <= 100`

</details>

<details>
<summary>Question 88 : Online Stock Span</summary>

[View Question](https://leetcode.com/problems/online-stock-span)

Design an algorithm that collects daily price quotes for some stock and returns **the span** of that stock's price for
the current day.

The **span** of the stock's price in one day is the maximum number of consecutive days (starting from that day and going
backward) for which the stock price was less than or equal to the price of that day.

* For example, if the prices of the stock in the last four days is `[7,2,1,2]` and the price of the stock today is `2`,
  then the span of today is `4` because starting from today, the price of the stock was less than or equal `2` for `4`
  consecutive days.
* Also, if the prices of the stock in the last four days is `[7,34,1,2]` and the price of the stock today is `8`, then
  the span of today is `3` because starting from today, the price of the stock was less than or equal `8` for `3`
  consecutive days.

Implement the `StockSpanner` class:

* `StockSpanner()` Initializes the object of the class.
* `int next(int price)` Returns the **span** of the stock's price given that today's price is `price`.

**Example 1:**

```
Input
["StockSpanner", "next", "next", "next", "next", "next", "next", "next"]
[[], [100], [80], [60], [70], [60], [75], [85]]
Output
[null, 1, 1, 1, 2, 1, 4, 6]

Explanation
StockSpanner stockSpanner = new StockSpanner();
stockSpanner.next(100); // return 1
stockSpanner.next(80);  // return 1
stockSpanner.next(60);  // return 1
stockSpanner.next(70);  // return 2
stockSpanner.next(60);  // return 1
stockSpanner.next(75);  // return 4, because the last 4 prices (including today's price of 75) were less than or equal to today's price.
stockSpanner.next(85);  // return 6

```

**Constraints:**

* `1 <= price <= 105`
* At most `104` calls will be made to `next`.

</details>

<details>
<summary>Question 89 : Partition Equal Subset Sum</summary>

[View Question](https://leetcode.com/problems/partition-equal-subset-sum)

Given an integer array `nums`, return `true` *if you can partition the array into two subsets such that the sum of the
elements in both subsets is equal or* `false` *otherwise*.

**Example 1:**

```
Input: nums = [1,5,11,5]
Output: true
Explanation: The array can be partitioned as [1, 5, 5] and [11].

```

**Example 2:**

```
Input: nums = [1,2,3,5]
Output: false
Explanation: The array cannot be partitioned into equal sum subsets.

```

**Constraints:**

* `1 <= nums.length <= 200`
* `1 <= nums[i] <= 100`

</details>

<details>
<summary>Question 90 : Redundant Connection</summary>

[View Question](https://leetcode.com/problems/redundant-connection)

Question content not found.

</details>

<details>
<summary>Question 91 : Find Median from Data Stream</summary>

[View Question](https://leetcode.com/problems/find-median-from-data-stream)

The **median** is the middle value in an ordered integer list. If the size of the list is even, there is no middle
value, and the median is the mean of the two middle values.

* For example, for `arr = [2,3,4]`, the median is `3`.
* For example, for `arr = [2,3]`, the median is `(2 + 3) / 2 = 2.5`.

Implement the MedianFinder class:

* `MedianFinder()` initializes the `MedianFinder` object.
* `void addNum(int num)` adds the integer `num` from the data stream to the data structure.
* `double findMedian()` returns the median of all elements so far. Answers within `10-5` of the actual answer will be
  accepted.

**Example 1:**

```
Input
["MedianFinder", "addNum", "addNum", "findMedian", "addNum", "findMedian"]
[[], [1], [2], [], [3], []]
Output
[null, null, null, 1.5, null, 2.0]

Explanation
MedianFinder medianFinder = new MedianFinder();
medianFinder.addNum(1);    // arr = [1]
medianFinder.addNum(2);    // arr = [1, 2]
medianFinder.findMedian(); // return 1.5 (i.e., (1 + 2) / 2)
medianFinder.addNum(3);    // arr[1, 2, 3]
medianFinder.findMedian(); // return 2.0

```

**Constraints:**

* `-105 <= num <= 105`
* There will be at least one element in the data structure before calling `findMedian`.
* At most `5 * 104` calls will be made to `addNum` and `findMedian`.

**Follow up:**

* If all integer numbers from the stream are in the range `[0, 100]`, how would you optimize your solution?
* If `99%` of all integer numbers from the stream are in the range `[0, 100]`, how would you optimize your solution?

</details>

<details>
<summary>Question 92 : Trapping Rain Water</summary>

[View Question](https://leetcode.com/problems/trapping-rain-water)

Given `n` non\-negative integers representing an elevation map where the width of each bar is `1`, compute how much
water it can trap after raining.

**Example 1:**

![](https://assets.leetcode.com/uploads/2018/10/22/rainwatertrap.png)

```
Input: height = [0,1,0,2,1,0,1,3,2,1,2,1]
Output: 6
Explanation: The above elevation map (black section) is represented by array [0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water (blue section) are being trapped.

```

**Example 2:**

```
Input: height = [4,2,0,3,2,5]
Output: 9

```

**Constraints:**

* `n == height.length`
* `1 <= n <= 2 * 104`
* `0 <= height[i] <= 105`

</details>

<details>
<summary>Question 93 : Max Points on a Line</summary>

[View Question](https://leetcode.com/problems/max-points-on-a-line)

Given an array of `points` where `points[i] = [xi, yi]` represents a point on the **X\-Y** plane, return *the maximum
number of points that lie on the same straight line*.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/02/25/plane1.jpg)

```
Input: points = [[1,1],[2,2],[3,3]]
Output: 3

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/02/25/plane2.jpg)

```
Input: points = [[1,1],[3,2],[5,3],[4,1],[2,3],[1,4]]
Output: 4

```

**Constraints:**

* `1 <= points.length <= 300`
* `points[i].length == 2`
* `-104 <= xi, yi <= 104`
* All the `points` are **unique**.

</details>

<details>
<summary>Question 94 : Serialize and Deserialize Binary Tree</summary>

[View Question](https://leetcode.com/problems/serialize-and-deserialize-binary-tree)

Question content not found.

</details>

<details>
<summary>Question 95 : Maximum Profit in Job Scheduling</summary>

[View Question](https://leetcode.com/problems/maximum-profit-in-job-scheduling)

We have `n` jobs, where every job is scheduled to be done from `startTime[i]` to `endTime[i]`, obtaining a profit
of `profit[i]`.

You're given the `startTime`, `endTime` and `profit` arrays, return the maximum profit you can take such that there are
no two jobs in the subset with overlapping time range.

If you choose a job that ends at time `X` you will be able to start another job that starts at time `X`.

**Example 1:**

**![](https://assets.leetcode.com/uploads/2019/10/10/sample1_1584.png)**

```
Input: startTime = [1,2,3,3], endTime = [3,4,5,6], profit = [50,10,40,70]
Output: 120
Explanation: The subset chosen is the first and fourth job. 
Time range [1-3]+[3-6] , we get profit of 120 = 50 + 70.

```

**Example 2:**

**![](https://assets.leetcode.com/uploads/2019/10/10/sample22_1584.png)**

```
Input: startTime = [1,2,3,4,6], endTime = [3,5,10,6,9], profit = [20,20,100,70,60]
Output: 150
Explanation: The subset chosen is the first, fourth and fifth job. 
Profit obtained 150 = 20 + 70 + 60.

```

**Example 3:**

**![](https://assets.leetcode.com/uploads/2019/10/10/sample3_1584.png)**

```
Input: startTime = [1,1,1], endTime = [2,3,4], profit = [5,6,4]
Output: 6

```

**Constraints:**

* `1 <= startTime.length == endTime.length == profit.length <= 5 * 104`
* `1 <= startTime[i] < endTime[i] <= 109`
* `1 <= profit[i] <= 104`

</details>

<details>
<summary>Question 96 : Sliding Window Maximum</summary>

[View Question](https://leetcode.com/problems/sliding-window-maximum)

You are given an array of integers `nums`, there is a sliding window of size `k` which is moving from the very left of
the array to the very right. You can only see the `k` numbers in the window. Each time the sliding window moves right by
one position.

Return *the max sliding window*.

**Example 1:**

```
Input: nums = [1,3,-1,-3,5,3,6,7], k = 3
Output: [3,3,5,5,6,7]
Explanation: 
Window position                Max
---------------               -----
[1  3  -1] -3  5  3  6  7       3
 1 [3  -1  -3] 5  3  6  7       3
 1  3 [-1  -3  5] 3  6  7       5
 1  3  -1 [-3  5  3] 6  7       5
 1  3  -1  -3 [5  3  6] 7       6
 1  3  -1  -3  5 [3  6  7]      7

```

**Example 2:**

```
Input: nums = [1], k = 1
Output: [1]

```

**Constraints:**

* `1 <= nums.length <= 105`
* `-104 <= nums[i] <= 104`
* `1 <= k <= nums.length`

</details>

<details>
<summary>Question 97 : Edit Distance</summary>

[View Question](https://leetcode.com/problems/edit-distance)

Given two strings `word1` and `word2`, return *the minimum number of operations required to convert `word1` to `word2`*.

You have the following three operations permitted on a word:

* Insert a character
* Delete a character
* Replace a character

**Example 1:**

```
Input: word1 = "horse", word2 = "ros"
Output: 3
Explanation: 
horse -> rorse (replace 'h' with 'r')
rorse -> rose (remove 'r')
rose -> ros (remove 'e')

```

**Example 2:**

```
Input: word1 = "intention", word2 = "execution"
Output: 5
Explanation: 
intention -> inention (remove 't')
inention -> enention (replace 'i' with 'e')
enention -> exention (replace 'n' with 'x')
exention -> exection (replace 'n' with 'c')
exection -> execution (insert 'u')

```

**Constraints:**

* `0 <= word1.length, word2.length <= 500`
* `word1` and `word2` consist of lowercase English letters.

</details>

<details>
<summary>Question 98 : Largest Rectangle in Histogram</summary>

[View Question](https://leetcode.com/problems/largest-rectangle-in-histogram)

Given an array of integers `heights` representing the histogram's bar height where the width of each bar is `1`, return
*the area of the largest rectangle in the histogram*.

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/01/04/histogram.jpg)

```
Input: heights = [2,1,5,6,2,3]
Output: 10
Explanation: The above is a histogram where width of each bar is 1.
The largest rectangle is shown in the red area, which has an area = 10 units.

```

**Example 2:**

![](https://assets.leetcode.com/uploads/2021/01/04/histogram-1.jpg)

```
Input: heights = [2,4]
Output: 4

```

**Constraints:**

* `1 <= heights.length <= 105`
* `0 <= heights[i] <= 104`

</details>

<details>
<summary>Question 99 : Number of Atoms</summary>

[View Question](https://leetcode.com/problems/number-of-atoms)

Given a string `formula` representing a chemical formula, return *the count of each atom*.

The atomic element always starts with an uppercase character, then zero or more lowercase letters, representing the
name.

One or more digits representing that element's count may follow if the count is greater than `1`. If the count is `1`,
no digits will follow.

* For example, `"H2O"` and `"H2O2"` are possible, but `"H1O2"` is impossible.

Two formulas are concatenated together to produce another formula.

* For example, `"H2O2He3Mg4"` is also a formula.

A formula placed in parentheses, and a count (optionally added) is also a formula.

* For example, `"(H2O2)"` and `"(H2O2)3"` are formulas.

Return the count of all elements as a string in the following form: the first name (in sorted order), followed by its
count (if that count is more than `1`), followed by the second name (in sorted order), followed by its count (if that
count is more than `1`), and so on.

The test cases are generated so that all the values in the output fit in a **32\-bit** integer.

**Example 1:**

```
Input: formula = "H2O"
Output: "H2O"
Explanation: The count of elements are {'H': 2, 'O': 1}.

```

**Example 2:**

```
Input: formula = "Mg(OH)2"
Output: "H2MgO2"
Explanation: The count of elements are {'H': 2, 'Mg': 1, 'O': 2}.

```

**Example 3:**

```
Input: formula = "K4(ON(SO3)2)2"
Output: "K4N2O14S4"
Explanation: The count of elements are {'K': 4, 'N': 2, 'O': 14, 'S': 4}.

```

**Constraints:**

* `1 <= formula.length <= 1000`
* `formula` consists of English letters, digits, `'('`, and `')'`.
* `formula` is always valid.

</details>

<details>
<summary>Question 100 : LFU Cache</summary>

[View Question](https://leetcode.com/problems/lfu-cache)

Design and implement a data structure for
a [Least Frequently Used (LFU)](https://en.wikipedia.org/wiki/Least_frequently_used) cache.

Implement the `LFUCache` class:

* `LFUCache(int capacity)` Initializes the object with the `capacity` of the data structure.
* `int get(int key)` Gets the value of the `key` if the `key` exists in the cache. Otherwise, returns `-1`.
* `void put(int key, int value)` Update the value of the `key` if present, or inserts the `key` if not already present.
  When the cache reaches its `capacity`, it should invalidate and remove the **least frequently used** key before
  inserting a new item. For this problem, when there is a **tie** (i.e., two or more keys with the same frequency), the
  **least recently used** `key` would be invalidated.

To determine the least frequently used key, a **use counter** is maintained for each key in the cache. The key with the
smallest **use counter** is the least frequently used key.

When a key is first inserted into the cache, its **use counter** is set to `1` (due to the `put` operation). The **use
counter** for a key in the cache is incremented either a `get` or `put` operation is called on it.

The functions `get` and `put` must each run in `O(1)` average time complexity.

**Example 1:**

```
Input
["LFUCache", "put", "put", "get", "put", "get", "get", "put", "get", "get", "get"]
[[2], [1, 1], [2, 2], [1], [3, 3], [2], [3], [4, 4], [1], [3], [4]]
Output
[null, null, null, 1, null, -1, 3, null, -1, 3, 4]

Explanation
// cnt(x) = the use counter for key x
// cache=[] will show the last used order for tiebreakers (leftmost element is  most recent)
LFUCache lfu = new LFUCache(2);
lfu.put(1, 1);   // cache=[1,_], cnt(1)=1
lfu.put(2, 2);   // cache=[2,1], cnt(2)=1, cnt(1)=1
lfu.get(1);      // return 1
                 // cache=[1,2], cnt(2)=1, cnt(1)=2
lfu.put(3, 3);   // 2 is the LFU key because cnt(2)=1 is the smallest, invalidate 2.
                 // cache=[3,1], cnt(3)=1, cnt(1)=2
lfu.get(2);      // return -1 (not found)
lfu.get(3);      // return 3
                 // cache=[3,1], cnt(3)=2, cnt(1)=2
lfu.put(4, 4);   // Both 1 and 3 have the same cnt, but 1 is LRU, invalidate 1.
                 // cache=[4,3], cnt(4)=1, cnt(3)=2
lfu.get(1);      // return -1 (not found)
lfu.get(3);      // return 3
                 // cache=[3,4], cnt(4)=1, cnt(3)=3
lfu.get(4);      // return 4
                 // cache=[4,3], cnt(4)=2, cnt(3)=3

```

**Constraints:**

* `1 <= capacity <= 104`
* `0 <= key <= 105`
* `0 <= value <= 109`
* At most `2 * 105` calls will be made to `get` and `put`.

</details>


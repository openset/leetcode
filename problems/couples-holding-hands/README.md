<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../largest-plus-sign "Largest Plus Sign")
　　　　　　　　　　　　　　　　
[Next >](../toeplitz-matrix "Toeplitz Matrix")

## [765. Couples Holding Hands (Hard)](https://leetcode.com/problems/couples-holding-hands "情侣牵手")

<p>There are <code>n</code> couples sitting in <code>2n</code> seats arranged in a row and want to hold hands.</p>

<p>The people and seats are represented by an integer array <code>row</code> where <code>row[i]</code> is the ID of the person sitting in the <code>i<sup>th</sup></code> seat. The couples are numbered in order, the first couple being <code>(0, 1)</code>, the second couple being <code>(2, 3)</code>, and so on with the last couple being <code>(2n - 2, 2n - 1)</code>.</p>

<p>Return <em>the minimum number of swaps so that every couple is sitting side by side</em>. A swap consists of choosing any two people, then they stand up and switch seats.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> row = [0,2,1,3]
<strong>Output:</strong> 1
<strong>Explanation:</strong> We only need to swap the second (row[1]) and third (row[2]) person.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> row = [3,2,0,1]
<strong>Output:</strong> 0
<strong>Explanation:</strong> All couples are already seated side by side.
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>2n == row.length</code></li>
	<li><code>2 &lt;= n &lt;= 30</code></li>
	<li><code>n</code> is even.</li>
	<li><code>0 &lt;= row[i] &lt; 2n</code></li>
	<li>All the elements of <code>row</code> are <strong>unique</strong>.</li>
</ul>

### Related Topics
  [[Greedy](../../tag/greedy/README.md)]
  [[Depth-First Search](../../tag/depth-first-search/README.md)]
  [[Breadth-First Search](../../tag/breadth-first-search/README.md)]
  [[Union Find](../../tag/union-find/README.md)]
  [[Graph](../../tag/graph/README.md)]

### Similar Questions
  1. [First Missing Positive](../first-missing-positive) (Hard)
  1. [Missing Number](../missing-number) (Easy)
  1. [K-Similar Strings](../k-similar-strings) (Hard)

### Hints
<details>
<summary>Hint 1</summary>
Say there are N two-seat couches.  For each couple, draw an edge from the couch of one partner to the couch of the other partner.
</details>

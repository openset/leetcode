<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../find-k-length-substrings-with-no-repeated-characters "Find K-Length Substrings With No Repeated Characters")
　　　　　　　　　　　　　　　　
[Next >](../path-with-maximum-minimum-value "Path With Maximum Minimum Value")

## [1101. The Earliest Moment When Everyone Become Friends (Medium)](https://leetcode.com/problems/the-earliest-moment-when-everyone-become-friends "彼此熟识的最早时间")



### Related Topics
  [[Union Find](../../tag/union-find/README.md)]
  [[Array](../../tag/array/README.md)]

### Similar Questions
  1. [Number of Provinces](../number-of-provinces) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
Sort the log items by their timestamp.
</details>

<details>
<summary>Hint 2</summary>
How can we model this problem as a graph problem?
</details>

<details>
<summary>Hint 3</summary>
Let's use a union-find data structure. At the beginning we have a graph with N nodes but no edges.
</details>

<details>
<summary>Hint 4</summary>
Then we loop through the events and if unite each node until the number of connected components reach to 1. Notice that each time two different connected components are united the number of connected components decreases by 1.
</details>

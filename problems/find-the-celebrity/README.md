<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../paint-fence "Paint Fence")
　　　　　　　　　　　　　　　　
[Next >](../first-bad-version "First Bad Version")

## [277. Find the Celebrity (Medium)](https://leetcode.com/problems/find-the-celebrity "搜寻名人")



### Related Topics
  [[Greedy](../../tag/greedy/README.md)]
  [[Graph](../../tag/graph/README.md)]
  [[Two Pointers](../../tag/two-pointers/README.md)]
  [[Interactive](../../tag/interactive/README.md)]

### Similar Questions
  1. [Find the Town Judge](../find-the-town-judge) (Easy)

### Hints
<details>
<summary>Hint 1</summary>
The best hint for this problem can be provided by the following figure:

<br>
<img src="https://assets.leetcode.com/uploads/2019/10/20/hint_find_celebrity.png" width="700"/>
</details>

<details>
<summary>Hint 2</summary>
Well, if you understood the gist of the above idea, you can extend it to find a candidate that can possibly be a celebrity. Why do we say a "candidate"? That is for you to think. This is clearly a greedy approach to find the answer. However, there is some information that would still remain to be verified without which we can't obtain an answer with certainty. To get that stake in the ground, we would need some more calls to the knows API.
</details>

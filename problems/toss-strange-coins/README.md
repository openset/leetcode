<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../meeting-scheduler "Meeting Scheduler")
　　　　　　　　　　　　　　　　
[Next >](../divide-chocolate "Divide Chocolate")

## [1230. Toss Strange Coins (Medium)](https://leetcode.com/problems/toss-strange-coins "抛掷硬币")



### Related Topics
  [[Math](../../tag/math/README.md)]
  [[Dynamic Programming](../../tag/dynamic-programming/README.md)]
  [[Probability and Statistics](../../tag/probability-and-statistics/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
What about solving the problem with DP?
</details>

<details>
<summary>Hint 2</summary>
Use DP with two states dp[pos][cnt], where pos represents the pos-th coin and cnt is the number of heads seen so far.
</details>

<details>
<summary>Hint 3</summary>
You can do the transitions with a little bit math.
</details>

<details>
<summary>Hint 4</summary>
For the base case, when pos == n return (cnt == target) to filter out the invalid scenarios.
</details>

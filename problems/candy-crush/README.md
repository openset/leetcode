<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../remove-comments "Remove Comments")
　　　　　　　　　　　　　　　　
[Next >](../find-pivot-index "Find Pivot Index")

## [723. Candy Crush (Medium)](https://leetcode.com/problems/candy-crush "粉碎糖果")



### Related Topics
  [[Array](../../tag/array/README.md)]
  [[Two Pointers](../../tag/two-pointers/README.md)]
  [[Matrix](../../tag/matrix/README.md)]
  [[Simulation](../../tag/simulation/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Carefully perform the "crush" and "gravity" steps.  In the crush step, flag each candy that should be removed, then go through and crush each flagged candy.  In the gravity step, collect the candy in each column and then rewrite the column appropriately.  Do these steps repeatedly until there's no work left to do.
</details>

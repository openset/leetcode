<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../median-employee-salary "Median Employee Salary")
　　　　　　　　　　　　　　　　
[Next >](../find-median-given-frequency-of-numbers "Find Median Given Frequency of Numbers")

## [570. Managers with at Least 5 Direct Reports (Medium)](https://leetcode.com/problems/managers-with-at-least-5-direct-reports "至少有5名直接下属的经理")



### Related Topics
  [[Database](../../tag/database/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Try to get all the mangerIDs that have count bigger than 5
</details>

<details>
<summary>Hint 2</summary>
Use the last hint's result as a table and do join with origin table at id equals to managerId
</details>

<details>
<summary>Hint 3</summary>
This is a very good example to show the performance of SQL code. Try to work out other solutions and you may be surprised by running time difference.
</details>

<details>
<summary>Hint 4</summary>
If your solution uses 'IN' function and runs more than 5 seconds, try to optimize it by using 'JOIN' instead.
</details>

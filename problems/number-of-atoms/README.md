<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../split-linked-list-in-parts "Split Linked List in Parts")
　　　　　　　　　　　　　　　　
[Next >](../minimum-window-subsequence "Minimum Window Subsequence")

## [726. Number of Atoms (Hard)](https://leetcode.com/problems/number-of-atoms "原子的数量")

<p>Given a string <code>formula</code> representing a chemical formula,&nbsp;return <em>the count of each atom</em>.</p>

<p>The atomic element always starts with an uppercase character, then zero or more lowercase letters, representing the name.</p>

<p>One or more digits representing that element&#39;s count may follow if the count is greater than <code>1</code>. If the count is <code>1</code>, no digits will follow.</p>

<ul>
	<li>For example, <code>&quot;H2O&quot;</code> and <code>&quot;H2O2&quot;</code> are possible, but <code>&quot;H1O2&quot;</code> is impossible.</li>
</ul>

<p>Two formulas are concatenated together to produce another formula.</p>

<ul>
	<li>For example, <code>&quot;H2O2He3Mg4&quot;</code> is also a formula.</li>
</ul>

<p>A formula placed in parentheses, and a count (optionally added) is also a formula.</p>

<ul>
	<li>For example, <code>&quot;(H2O2)&quot;</code> and <code>&quot;(H2O2)3&quot;</code> are formulas.</li>
</ul>

<p>Return the count of all elements as a string in the following form: the first name (in sorted order), followed by its count (if that count is more than <code>1</code>), followed by the second name (in sorted order), followed by its count (if that count is more than <code>1</code>), and so on.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> formula = &quot;H2O&quot;
<strong>Output:</strong> &quot;H2O&quot;
<strong>Explanation:</strong> The count of elements are {&#39;H&#39;: 2, &#39;O&#39;: 1}.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> formula = &quot;Mg(OH)2&quot;
<strong>Output:</strong> &quot;H2MgO2&quot;
<strong>Explanation:</strong> The count of elements are {&#39;H&#39;: 2, &#39;Mg&#39;: 1, &#39;O&#39;: 2}.
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> formula = &quot;K4(ON(SO3)2)2&quot;
<strong>Output:</strong> &quot;K4N2O14S4&quot;
<strong>Explanation:</strong> The count of elements are {&#39;K&#39;: 4, &#39;N&#39;: 2, &#39;O&#39;: 14, &#39;S&#39;: 4}.
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> formula = &quot;Be32&quot;
<strong>Output:</strong> &quot;Be32&quot;
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= formula.length&nbsp;&lt;= 1000</code></li>
	<li><code>formula</code> consists of English letters, digits, <code>&#39;(&#39;</code>, and <code>&#39;)&#39;</code>.</li>
	<li><code>formula</code> is always valid.</li>
	<li>All the values in the output will fit in a 32-bit integer.</li>
</ul>

### Related Topics
  [[Stack](../../tag/stack/README.md)]
  [[Hash Table](../../tag/hash-table/README.md)]
  [[String](../../tag/string/README.md)]

### Similar Questions
  1. [Decode String](../decode-string) (Medium)
  1. [Encode String with Shortest Length](../encode-string-with-shortest-length) (Hard)
  1. [Parse Lisp Expression](../parse-lisp-expression) (Hard)

### Hints
<details>
<summary>Hint 1</summary>
To parse formula[i:], when we see a `'('`, we will parse recursively whatever is inside the brackets (up to the correct closing ending bracket) and add it to our count, multiplying by the following multiplicity if there is one.

Otherwise, we should see an uppercase character: we will parse the rest of the letters to get the name, and add that (plus the multiplicity if there is one.)
</details>

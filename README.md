Download Link: https://assignmentchef.com/product/solved-cs3001301-homework4
<br>
<strong>Problem 4.1.</strong> In the code of LOOKUP-CHAIN (checking the slides or p.388 from the textbook), if the first two lines of code, namely,

<ul>

 <li><strong>if</strong> <em>m</em>[<em>i</em>, <em>j</em>] &lt; </li>

 <li><strong>return</strong> <em>m</em>[<em>i</em>, <em>j</em>]</li>

</ul>

are removed, what will happen?

<strong>Problem 4.2.</strong> Consider a variant of the matrix-chain multiplication problem in which the goal is to parenthesize the sequence of matrices so as to maximize, rather than minimize, the number of scalar multiplications. Does this problem exhibit optimal substructure?

<strong>Problem 4.3.</strong> Determine an LCS of 1, 0, 1, 0, 0, 1, 0, 1 and 0, 1, 0, 1, 1, 0, 1, 1, 0. Moreover, as discussed in our class, generalize the recursive formula used in the textbook Eq. 15.9 (p.393) to the following one:

                                       0                                           if <em>i </em> 0 or <em>j </em> 0 ,

<em><sup>c</sup></em><sup>[<em>i</em>, <em>j</em>] </sup><sup></sup>max(<em>c</em>[<em>i </em>1, <em>j </em>1] (<em>x</em><em><sub>i </sub></em> <em>y </em><em><sub>j </sub></em>),<em>c</em>[<em>i</em>, <em>j </em>1],<em>c</em>[<em>i </em>1, <em>j</em>])  if <em>i</em>, <em>j </em> 0 ,        <sub></sub>

(<em>x<sub>i</sub></em> == <em>y<sub>j</sub></em> is 1 if <em>x<sub>i</sub></em> = <em>y<sub>j</sub></em> or 0 if not), so that <u>all</u> LCS’s of two sequences can be found. Use the recursive formula to find all the LCS’s.

<strong>Problem 4.4.</strong> Give an <em>O</em>(<em>n</em><sup>2</sup>)-time algorithm to find the longest monotonically increasing subsequence of a sequence of <em>n</em> numbers. Discuss two cases separately: (1) simple increasing subsequences (2) strictly increasing subsequences. (2pts)

<strong>Problem 4.5.</strong> Not just any greedy approach to the activity-selection problem produces a maximum-size set of mutually compatible activities. Give an example to show that the approach of selecting the activity of least duration from among those that are compatible with previously selected activities does not work. Do the same for the approaches of always selecting the compatible activity that overlaps the fewest other remaining activities and always selecting the compatible remaining activity with the earliest start time.



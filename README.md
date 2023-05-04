Download Link: https://assignmentchef.com/product/solved-cse-321-homework-4
<br>
1- ) An m × n array A of real numbers is called a <strong><em>special</em></strong> array if for all i, j , k, and l such that 1 ≤ i &lt; k ≤ m and 1 ≤ j &lt; l ≤ n, we have:

<h1>A[i, j ] + A[k, l] ≤ A[i, l] + A[k, j ]</h1>

For example, the following array is a <strong><em>special</em></strong> array:

<table width="605">

 <tbody>

  <tr>

   <td width="121">10</td>

   <td width="121">17</td>

   <td width="121">13</td>

   <td width="121">28</td>

   <td width="121">23</td>

  </tr>

  <tr>

   <td width="121">17</td>

   <td width="121">22</td>

   <td width="121">16</td>

   <td width="121">29</td>

   <td width="121">23</td>

  </tr>

  <tr>

   <td width="121">24</td>

   <td width="121">28</td>

   <td width="121">22</td>

   <td width="121">34</td>

   <td width="121">24</td>

  </tr>

  <tr>

   <td width="121">11</td>

   <td width="121">13</td>

   <td width="121">6</td>

   <td width="121">17</td>

   <td width="121">7</td>

  </tr>

  <tr>

   <td width="121">45</td>

   <td width="121">44</td>

   <td width="121">32</td>

   <td width="121">37</td>

   <td width="121">23</td>

  </tr>

  <tr>

   <td width="121">36</td>

   <td width="121">33</td>

   <td width="121">19</td>

   <td width="121">21</td>

   <td width="121">6</td>

  </tr>

  <tr>

   <td width="121">75</td>

   <td width="121">66</td>

   <td width="121">51</td>

   <td width="121">53</td>

   <td width="121">34</td>

  </tr>

 </tbody>

</table>




<ol>

 <li>Prove that an array is <strong><em>special</em></strong> if and only if for all i = 1, 2, …, m − 1 and j = 1, 2, …, n − 1, we have:</li>

</ol>

A[i, j ] + A[i + 1, j + 1] ≤ A[i, j + 1] + A[i + 1, j ]

<ol>

 <li>Give an algorithm (not necessarily divide-and-conquer) that converts a 2D array into the <strong><em>special</em></strong> array only if it can be done with changing one single element in the array. Write pseudo code, implement and explain your algorithm.</li>

 <li>Give a divide-and-conquer algorithm that finds the leftmost minimum element in each row. Implement your algorithm and explain it in the report file.</li>

 <li>Write the recurrence relation for the running time of your algorithm in option c)</li>

</ol>

<ul>

 <li>) Given two sorted arrays A and B, design a divide-and-conquer algorithm that finds the k<sup>th</sup> element of the merged array of these two sorted arrays. Do not try to merge the array at first and find the k<sup>th</sup> element later! Implement your algorithm and analyze its worst-case running time. You can assume that the arrays A and B have m and n items, respectively. Explain your algorithm in your report file.</li>

 <li>) Given an array of integers A[1; … ;n], propose a divide-and-conquer algorithm that finds a contiguous subset having the largest sum within A. For example, let A = [5, -6, 6, 7, -6, 7, -4, 3]. The contiguous subset with the largest sum is [6, 7, -6, 7] whose sum is 14. Implement your algorithm and analyze its worst-case running time. Explain your algorithm in your report file.</li>

</ul>

4-) A bipartite graph is a graph whose vertices can be divided into two disjoint and independent sets U and V such that every edge connects a vertex in U to one in V. Design a decrease and conquer algorithm that checks whether a given graph is a bipartite graph or not. Implement your algorithm and analyze its worst-case running time. Explain your algorithm in report file.

5-) Suppose that you manage a warehouse: buy some goods, store the goods for one day and sell them the next day. The cost of storing the goods changes daily depending on the occupancy ratio in the warehouse. On the other hand, the selling price of the goods varies according to markets. You want to buy and sell 500 goods and make as much money as possible from these sales. Design a divide-and-conquer algorithm that finds the best day to buy the goods. Consider the following example to understand the problem:

Suppose that you have ten days to buy and sell the goods.

The array of storage costs for the goods is:

C = [5, 11, 2, 21, 5, 7, 8, 12, 13, −]

The array of prices for the goods in markets is:

<h1>P = [−, 7, 9, 5, 21, 7, 13, 10, 14, 20]</h1>




<table width="605">

 <tbody>

  <tr>

   <td width="55">Day</td>

   <td width="55">1</td>

   <td width="55">2</td>

   <td width="55">3</td>

   <td width="55">4</td>

   <td width="55">5</td>

   <td width="55">6</td>

   <td width="55">7</td>

   <td width="55">8</td>

   <td width="55">9</td>

   <td width="55">10</td>

  </tr>

  <tr>

   <td width="55">Cost</td>

   <td width="55">5</td>

   <td width="55">11</td>

   <td width="55">2</td>

   <td width="55">21</td>

   <td width="55">5</td>

   <td width="55">7</td>

   <td width="55">8</td>

   <td width="55">12</td>

   <td width="55">13</td>

   <td width="55">–</td>

  </tr>

  <tr>

   <td width="55">Price</td>

   <td width="55">–</td>

   <td width="55">7</td>

   <td width="55">9</td>

   <td width="55">5</td>

   <td width="55">21</td>

   <td width="55">7</td>

   <td width="55">13</td>

   <td width="55">10</td>

   <td width="55">14</td>

   <td width="55">20</td>

  </tr>

  <tr>

   <td width="55">Gain</td>

   <td width="55"> </td>

   <td width="55">2</td>

   <td width="55">-2</td>

   <td width="55">3</td>

   <td width="55">0</td>

   <td width="55">2</td>

   <td width="55">6</td>

   <td width="55">2</td>

   <td width="55">2</td>

   <td width="55">7</td>

  </tr>

 </tbody>

</table>




The best day to buy goods is the 9<sup>th</sup> day because if you buy the goods on the 9<sup>th</sup> day and sell them on the 10<sup>th</sup> day, you can make 7 units of money, which is the maximum possible gain in the schedule.




Your algorithm must report if there is no day to make money.  Implement your algorithm and analyze its worst-case running time. Explain your algorithm in the report file.
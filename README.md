Download Link: https://assignmentchef.com/product/solved-eso207-data-structures-and-algorithms-theory-assignment-1
<br>






Part 1

<strong>Problem1</strong>. (10 points) Let <em>A </em>be an array consisting of <em>n </em>elements such that there exists indices <em>i,j,k </em>∈ [0<em>,n </em>− 1], where 0 ≤ <em>i &lt; k &lt; j </em>≤ <em>n </em>− 1, and <em>A</em>[0] <em>&lt; A</em>[1] <em>&lt; … &lt; A</em>[<em>i </em>− 1] <em>&lt; A</em>[<em>i</em>] <em>&gt; A</em>[<em>i </em>+ 1] <em>&gt; … &gt; A</em>[<em>k</em>] <em>&lt; A</em>[<em>k </em>+ 1] <em>&lt; A</em>[<em>k </em>+ 2] <em>&lt; …A</em>[<em>j </em>− 1] <em>&lt; A</em>[<em>j</em>] <em>&gt; A</em>[<em>j </em>+ 1] <em>&gt; A</em>[<em>j </em>+ 2]<em>…. &gt; A</em>[<em>n </em>− 1]. Design an <em>O</em>(log<em>n</em>) time algorithm to find <em>i </em>and <em>j </em>(the two local maxima ) in the array. Describe your approach and prove the correctness of your algorithm.

<strong>Problem2</strong>. (10 points) Given a doubly linked list <em>a</em><sub>1</sub><em>,a</em><sub>2</sub><em>,…,a<sub>n</sub></em>, rotating it from location <em>p </em>to location <em>q </em>to the right by <em>k </em>places gives the list <em>a</em><sub>1</sub><em>,…,a<sub>p</sub></em><sub>−1</sub><em>,a<sub>q</sub></em><sub>−<em>k</em>+1</sub><em>,…,a<sub>q</sub>,a<sub>p</sub>,…,a<sub>q</sub></em><sub>−<em>k</em></sub><em>,a<sub>q</sub></em><sub>+1</sub><em>,…,a<sub>n</sub></em>.

For example if <em>p </em>= 3, <em>q </em>= 7 and <em>k </em>= 2 then your algorithm should return <em>L’ </em>.

<table width="429">

 <tbody>

  <tr>

   <td width="127">Location</td>

   <td width="29">1</td>

   <td width="29">2</td>

   <td width="31">3</td>

   <td width="31">4</td>

   <td width="31">5</td>

   <td width="31">6</td>

   <td width="31">7</td>

   <td width="29">8</td>

   <td width="29">9</td>

   <td width="29">10</td>

  </tr>

  <tr>

   <td width="127">Before Rotation(L)</td>

   <td width="29">22</td>

   <td width="29">13</td>

   <td width="31">17</td>

   <td width="31">35</td>

   <td width="31">11</td>

   <td width="31">56</td>

   <td width="31">49</td>

   <td width="29">64</td>

   <td width="29">28</td>

   <td width="29">62</td>

  </tr>

  <tr>

   <td width="127">After Rotation(L’)</td>

   <td width="29">22</td>

   <td width="29">13</td>

   <td width="31"><strong>56</strong></td>

   <td width="31"><strong>49</strong></td>

   <td width="31"><strong>17</strong></td>

   <td width="31"><strong>35</strong></td>

   <td width="31"><strong>11</strong></td>

   <td width="29">64</td>

   <td width="29">28</td>

   <td width="29">62</td>

  </tr>

 </tbody>

</table>

Design an <em>O</em>(<em>n</em>) time algorithm to rotate a sub-list from location <em>p </em>to location <em>q </em>to the right by <em>k </em>places using only <em>O</em>(1) (not <em>O</em>(<em>k</em>)) extra space.

<strong>Problem3</strong>. (10 points) Suppose you are given two sorted arrays <em>A</em>[0<em>,…,n</em>−1] and <em>B</em>[0<em>,…,n</em>−1]. Design an algorithm to find the median of the array obtained after merging the above two arrays (i.e. array of length 2<em>n</em>). The time complexity of the algorithm should be <em>O</em>(log<em>n</em>). You can use only <em>O</em>(1) extra space only. Prove the correctness of your algorithm.

Example :

Page 1 of 2

<table width="146">

 <tbody>

  <tr>

   <td width="29">40</td>

   <td width="29">53</td>

   <td width="29">59</td>

   <td width="29">61</td>

   <td width="29">66</td>

  </tr>

 </tbody>

</table>

B

Output : (40 + 53)<em>/</em>2 = 46<em>.</em>5

<strong>Problem4</strong>. (10 points) Suppose you are given a sorted array <em>A </em>storing <em>n </em>distinct positive integers, and three positive integers <em>a</em>,<em>b </em>and <em>c</em>. Design an <em>O</em>(<em>n</em>) time algorithm to determine if there exist any two distinct integers <em>x,y </em>∈ <em>A </em>such that <em>a</em><sup>2 </sup>= <em>bx </em>+ <em>cy</em>. Prove correctness of your algorithm.

<h1>Part 2</h1>

<strong>Problem5</strong>. (10 points) Prove the following statements:

<ul>

 <li>min(<em>n</em><sup>2</sup><em>,</em>10<sup>12</sup>) = O(1)</li>

 <li><em>n</em><sup>2 </sup>+ <em>n</em>log<em>n </em>= O(<em>n</em><sup>2</sup>)</li>

 <li><em>n</em><sup>3 </sup>+ 3<em>n</em><sup>2 </sup>+ 8 6= O(<em>n</em><sup>2</sup>)</li>

 <li>4<em><sup>n </sup></em>6= O(2<em><sup>n</sup></em>)</li>

 <li>log(<em>n</em>!) = O(<em>n</em>log<em>n</em>)</li>

</ul>

<strong>Problem6</strong>. (10 points) Design an O(log<em>n</em>) time algorithm that takes as input two arrays <em>A </em>and <em>B </em>sorted in ascending order and outputs an index <em>k </em>for which <em>A</em>[<em>k</em>] = <em>B</em>[<em>n</em>−1−<em>k</em>]. If such an index does not exist then your algorithm must return -1 to indicate failure. Describe your approach, provide the pseudocode and prove that your algorithm is correct and has a worst time complexity of O(log<em>n</em>).

<table>

 <tbody>

  <tr>

   <td width="245"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<strong>Example: </strong>For following input <em>A </em>and <em>B </em>(<em>n </em>= 8), the correct output is <em>k </em>= 5, since <em>A</em>[5] = <em>B</em>[8−1−5] = <em>B</em>[2] = 10.

<table width="310">

 <tbody>

  <tr>

   <td width="56">index <em>i</em></td>

   <td width="34">0</td>

   <td width="27">1</td>

   <td width="31">2</td>

   <td width="29">3</td>

   <td width="29">4</td>

   <td width="31">5</td>

   <td width="36">6</td>

   <td width="36">7</td>

  </tr>

  <tr>

   <td width="56"><em>A</em>[<em>i</em>]</td>

   <td width="34">-5</td>

   <td width="27">-2</td>

   <td width="31">-1</td>

   <td width="29">0</td>

   <td width="29">5</td>

   <td width="31"><strong>10</strong></td>

   <td width="36">120</td>

   <td width="36">150</td>

  </tr>

  <tr>

   <td width="56"><em>B</em>[<em>i</em>]</td>

   <td width="34">-10</td>

   <td width="27">5</td>

   <td width="31"><strong>10</strong></td>

   <td width="29">15</td>

   <td width="29">17</td>

   <td width="31">40</td>

   <td width="36">47</td>

   <td width="36">90</td>

  </tr>

 </tbody>

</table>

<strong>Problem7</strong>. (10 points) Consider two sets of points      )] and

sampled from two parallel lines <em>l<sub>A </sub></em>and <em>l<sub>B</sub></em>, respectively. Design an <em>O</em>(<em>n</em>log<em>n</em>) time algorithm that takes <em>A </em>and <em>B </em>as input and returns two points (<em>a<sup>p</sup><sub>x</sub>,a<sup>p</sup><sub>y</sub></em>) and (<em>b<sup>q</sup><sub>x</sub>,b<sup>q</sup><sub>y</sub></em>) (0 ≤ <em>p,q </em>≤ <em>n</em>−1) from sets <em>A </em>and <em>B </em>that are closest to each other. Describe your algorithm and provide the pseudocode. Prove the correctness of your algorithm and show that it runs in O(<em>n</em>log<em>n</em>) time.

<strong>Problem8</strong>. (10 points) You are given an unsorted array <em>A</em>. Design an algorithm that, given a query [<em>a,b</em>] (<em>a,b </em>∈R<em>,a </em>≤ <em>b</em>), finds the following in O(log<em>n</em>) time:

<ol>

 <li>the total number of elements in <em>A </em>whose values lie in the interval [<em>a,b</em>]</li>

 <li>the value in [<em>a,b</em>] which occurs the most in <em>A</em>.</li>

</ol>

<strong>Example:</strong>

<em>A </em>= [1<em>.</em>5<em>,</em>1<em>.</em>5<em>,</em>−2<em>,</em>0<em>,</em>2<em>,</em>0<em>,</em>0<em>,</em>3<em>.</em>2<em>,</em>0<em>,</em>3<em>,</em>2<em>.</em>4<em>,</em>−1<em>,</em>1<em>,</em>1<em>,</em>1<em>.</em>7<em>,</em>1<em>.</em>5<em>,</em>1<em>.</em>2<em>,</em>−3<em>,</em>−2<em>.</em>1<em>,</em>−5]

<ul>

 <li>For query [0<em>.</em>8<em>,</em>3], there are 10 elements ([1<em>.</em>5<em>,</em>1<em>.</em>5<em>,</em>2<em>,</em>3<em>,</em>2<em>.</em>4<em>,</em>1<em>,</em>1<em>,</em>1<em>.</em>7<em>,</em>1<em>.</em>5<em>,</em>1<em>.</em>2]) in the query interval, and 1<em>.</em>5 is the most frequent one.</li>

 <li>For query [−0<em>.</em>2<em>,</em>1<em>.</em>3], there are 7 elements ([0<em>,</em>0<em>,</em>0<em>,</em>0<em>,</em>1<em>,</em>1<em>,</em>1<em>.</em>2]) in the query interval, and 0 is the most frequent one.</li>

</ul>

Explain your approach and provide the pseudocode. You may use O(<em>n</em>log<em>n</em>) time to preprocess the input data once. You can keep O(<em>n</em>log<em>n</em>) additional space.



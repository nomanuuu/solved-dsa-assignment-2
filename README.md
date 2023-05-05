Download Link: https://assignmentchef.com/product/solved-dsa-assignment-2
<br>
<h1>Problem 1: AVL Tree</h1>

<strong>AIM </strong>:To have end to end knowledge of the balanced binary search tree and how it can be used to solve a wide range of problems efficiently.

<strong>TASK: </strong>Implement AVL Tree with Following Operations.

<strong>Operations to implement:</strong>

<table width="654">

 <tbody>

  <tr>

   <td width="51"> </td>

   <td width="470"><strong>Operations</strong></td>

   <td width="133"><strong>Complexity</strong></td>

  </tr>

  <tr>

   <td width="51">1</td>

   <td width="470">Insertion</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">2</td>

   <td width="470">Deletion</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">3</td>

   <td width="470">Search</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">4</td>

   <td width="470">Count occurrences of element</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">5</td>

   <td width="470">lower_bound</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">6</td>

   <td width="470">upper_bound</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">7</td>

   <td width="470">Closest Element to some value</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">8</td>

   <td width="470">K-th largest element</td>

   <td width="133">O(log N)</td>

  </tr>

  <tr>

   <td width="51">9</td>

   <td width="470">Count the number of elements in the tree whose values fall into a given range.</td>

   <td width="133">O(log N)</td>

  </tr>

 </tbody>

</table>

<strong><u>IMPORTANT POINTS:</u> </strong>

<ol>

 <li>Implement it with <strong>class</strong> or <strong>struct</strong>. It should be <strong>generic</strong>.</li>

 <li><strong>Duplicates</strong> are allowed. (We know that AVL tree doesn’t have duplicates but in this task you have to handle it.)</li>

 <li>For <strong>strings</strong>, you can simply compare them but for <strong>Class data type</strong>, you have to pass the comparator object so that you can compare two objects.</li>

</ol>

<strong>Parameter to Judge:</strong> Time and space complexity.

<strong>Format to submit:</strong> RollNo_Q1.cpp

<strong>References: </strong><a href="https://en.wikipedia.org/wiki/AVL_tree"><strong>https://en.wikipedia.org/wiki/AVL_tree</strong></a>

<h1>Problem 2: Hashing</h1>

<strong>Task</strong>: Implement an Unordered Map.

<strong>Aim</strong>: To learn how Hashing works and importance of Hash Functions. Also look how Universal Hashing is implemented.

<strong>Parameter to Judge</strong>: Time and space complexity.

Hashing should be efficient and appropriate reasons must be given on choice of hash function.

<strong>Functions to implement:</strong>

<ol>

 <li><strong>insert(key, value) </strong>– insert key value pair.</li>

 <li><strong>erase(key)</strong> – erase if key is present otherwise do nothing.</li>

 <li><strong>find(key)</strong> – returns true or false.</li>

 <li><strong>map[key]</strong> – returns the value mapped to key.</li>

</ol>

<strong>Note</strong>: Unordered Map should be generic.

<strong>Format to submit</strong>: RollNo_Q2.cpp

<strong>References:</strong>

https://en.wikipedia.org/wiki/Hash_function https://en.wikipedia.org/wiki/Universal_hashing <strong><u>Problem 3: Ordered Map</u></strong>

<strong>Task : </strong>Implement an Ordered Map which supports the given Operations

<strong>Operations:</strong>

<ol>

 <li><strong>insert(key, value)</strong> – Insert the key value pair. If the key is already present, update it’s current value. [O(log n)]</li>

 <li><strong>erase(key)</strong> – Erase the given key from the map if it is present. [O(log n)]</li>

 <li><strong>find(key)</strong> – returns true if key was found else return 0. [O(logn)]</li>

 <li><strong>map_obj[key]</strong> (subscript operator) – Access the element with the given key(if it is present in the map). Also, you should be able to modify the value at this key using this operator. If the value is not present, then insert this key with it’s corresponding assigned value. [O(log n)]</li>

 <li><strong>size() </strong>– returns the number of keys present in the Map. [O(1)]</li>

 <li><strong>clear()</strong> – removes all the elements from the Map. [O(n)]</li>

</ol>

<strong>Note:</strong>

<ol>

 <li>You should implement this Ordered Map in a class or struct. II. Duplicates are not allowed.</li>

</ol>

III.       All the operations should meet their expected time complexity. IV.      You can add constructors and destructors as required.

<strong>Parameters to Judge : </strong>Correctness, Space and Time Complexity

<strong>Submission Format : </strong>RollNumber_Q3.cpp

<strong>Note : For all the questions, accuracy will be tested on the basis of test cases passed which will be provided during evaluation.</strong>
Download Link: https://assignmentchef.com/product/solved-csci3110-lab6-binary-search-tree-and-hash-table
<br>
<strong>Objective</strong>: To be familiar binary search tree and hash table.

<strong>Description</strong>: Implement a binary search tree using hash table.




In this project, you are required to implement a binary search tree using hash table. In C++, hash table is represented by the STL class template: unordered_map. Please check this page for member functions and examples of unordered_map: <a href="http://en.cppreference.com/w/cpp/container/unordered_map">http://en.cppreference.com/w/cpp/container/unordered_map</a><a href="http://en.cppreference.com/w/cpp/container/unordered_map">.</a>




In the binary search tree, each node contains a student object. The student object should contains M#, phone number, and address. M# is a string starting with char ‘M’ and followed by digits, such as “M12345678”. In the hash map, the key is student’s M#, and the value associated with the key is the following structure:

struct TreeNode {

Student item;   string  left_child_M#;

string               right_child_M#;

};

If the M# of its left or right child doesn’t exist, set its value to “M00000000”.

<strong> </strong>

<strong>Requirements: </strong>

<ul>

 <li>Define and implement Student class. Make sure it contains M#, phone number, and address, all getters and setters, and constructors. In addition, override &lt; operator to compare student objects by M#, and the &lt;&lt; operator for output.</li>

 <li>Define and implement BST class to represent binary search tree. In this class, you should have:

  <ul>

   <li>A member data of the type unordered_map&lt; string, TreeNode&gt; to hold nodes in the binary search tree.</li>

   <li>Member functions for in-order traversal, searching by M#, inserting a new Student object, and deleting by M#.</li>

  </ul></li>

 <li>In the main function, which should be included in ola6.cpp file, please perform the following operation in the given step:

  <ul>

   <li>Create an empty binary search tree;</li>

   <li>Insert the following M#s to the BST in the given order: M00000005, M00000003,</li>

  </ul></li>

</ul>

M00000002, M00000001, M00000004, M00000006, M00000009, M00000008,

M00000007. M00000010. Feel free to come up with other information for each student object.

<ul>

 <li>Perform in-order traversal to print all students in the tree; o Search the student with M# = ‘M00000007’. Print all information of the student.</li>

 <li>Delete the student with M# = ‘M00000002’; o Perform in-order traversal to print all students in the tree; o Delete the student with M# = ‘M00000005’.</li>

 <li>Perform in-order traversal to print all students in the tree;</li>

</ul>




<strong>How to download assignment files: </strong>

Go to the URL: <a href="http://www.cs.mtsu.edu/~zdong/3110/public/OLA/OLA2.zip">http://www.cs.mtsu.edu/~zdong/3110/public/OLA/</a> and download the file OLA6.zip, which contains the following files:

<ul>

 <li>doc: this file</li>

 <li>doc: a rubric used to grade this assignment</li>

</ul>

<strong> </strong>
Download Link: https://assignmentchef.com/product/solved-icsi403-homework-4
<br>
<strong>Problem :</strong>

Given the sequence of numbers: 20, 7, 34, 29, 43, 40, 8, 12, 30, 42




<ol>

 <li>Show the resulting BST after inserting the numbers as keys.</li>

 <li>What will be the resulting tree if you delete the root? Show the tree and explain the steps taken in deleting the root according to the delete procedure we discussed in class.</li>

 <li>Can you reorder the original sequence of numbers to obtain a tree of a smaller height? If, yes, show the permutation of the sequence and the new tree. If no, argue why a smaller height is not obtainable.</li>

</ol>




<strong>Problem 2  </strong>

We discussed a delete operation that if necessary, swaps with a successor of the deleted node when the deleted node has two children.




<ol>

 <li>Argue that swapping one can also swap with the predecessor, and that it will result in a correct BST, once the predecessor is spliced out.</li>

 <li>Demonstrate the delete operation with predecessor swap on the example from Q1(a) by deleting the root 20. Show the resulting tree?</li>

 <li>Swapping predecessor and successors may result in a relatively balanced tree. Provide the pseudo code of a procedure that in case where both children of the node to be deleted exist:

  <ol>

   <li>swaps with the predecessor if the left subtree of the deleted node is larger</li>

  </ol></li>

</ol>

(contains more nodes) than the right subtree,

<ol>

 <li>swaps with the successor otherwise,</li>

</ol>




The procedure should work as the original delete operation for the cases of zero or one children.




<strong>Problem 3 :  </strong>

Suppose we have integer key values between 1 and 1000 stored in a binary search tree and we want to search for the key value 363. For each of the following sequences, indicate whether or not it can be a valid sequence of nodes examined during the search. If the sequence is valid, draw the search path clearly indicating whether a node is the left child or the right child of its parent. If the sequence is invalid, explain why it cannot arise in the search.

<ol start="363">

 <li>2, 399, 387, 219, 266, 382, 381, 278, 363.</li>

 <li>935, 278, 347, 621, 299, 392, 358, 363.</li>

</ol>




<strong>             </strong>




<strong>Problem 4 </strong><strong>  </strong>

Consider the following disjoint set (DS) S : {{0, 1, 2]; {3, 5}} assuming the first listed element is the representative for each set.




(a) Show the data structure of the disjoint set using both the list and tree representation. Multiple tree representations are possible based on how unions were applied to get to these sets. Include possible rank values as well.

Consider the following commands applied to S: make set(4) union(1,5) union(4,5)




(b) Show the resulting data structure after applying the commands on the list representation, assuming the weighted union heuristic is employed.

(c)[ Show the resulting data structure after applying the commands on the tree representation, assuming both the path-compression and union-by-rank heuristics are employed (show the ranks before and after the commands).




<strong>Problem 5 </strong><strong> </strong>

(a) Give an algorithm (pseudo code) to detect whether a given undirected graph contains a cycle: a sequence of nodes that starts and ends in the same node without traversing the same edge twice.

(b) If the graph contains a cycle, then your algorithm should output one example cycle as the sequence of nodes that are on the cycle. (It should not output all cycles in the graph, just one of them.) The running time of your algorithm should be O(m + n) for a graph with n nodes and m edges.

(c) Demonstrate the steps of your algorithm on a simple “ring” graph of 5 nodes:

E : {(1; 2); (2; 3); (3; 4); (4; 5); (5; 1)}.

<strong>Note:</strong> To get points for (b) and (c) you need to have solved (a).




<strong>Problem 6 </strong><strong> </strong>

We have a connected undirected graph G = (V, E), and a specific vertex u ϵ V. Suppose we compute a depth-first search tree rooted at u, and obtain a tree T that includes all nodes of G. Suppose we then compute a breadth-first search tree rooted at u, and obtain the same tree T.




Prove that G = T. (In other words, if T is both a depth-first search tree and a breadth-first search

tree rooted at u, then G cannot contain any edges that do not belong to T.) <strong>Hint:</strong> Consider a proof by contradiction.



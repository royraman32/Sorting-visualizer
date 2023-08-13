# Sorting-Visualizer

1. Introduction

Nowadays sorting algorithms are widely used in computer software. For example, if you open file explorer on your PC, you may see files sorted in different ways. Searching in sorted data is more efficient than in not sorted ones. Students of computer science start learning different algorithms in the first year of studies and sorting algorithms are among them. 
Since I faced the problems of sorting during the course of algorithm design in the first year of my studies, there is an understanding that the visual representation is a vital part of the studying process. During working on the thesis it was very exciting to learn different techniques of sorting algorithms into the depth. 
The main goal of the thesis was to create a program which would serve as a tool for understanding how most known sorting algorithms work. There was an attempt to make the best possible user experience. The demonstration software is made in a user-friendly and easy-to-use style. To gain maximal benefit from learning you can try each sorting algorithm on your data. 
The text of the thesis describes principles of the most known sorting algorithms which are demonstrated in the computer program. It might be used as a source for learning algorithms by students. Also, the program might be easily used as a demonstration by lecturers and tutors during classes. Besides, there is programmer documentation and user guide to the provided software. 
Readers of this text are expected to have some programming experience to know basic data structures such as arrays, lists, trees and understand recursive procedures. Also, knowledge of some simple algorithms and their implementations could be helpful. In order to understand the topic better, knowledge of linear algebra and calculus is involved.
 

2. Sorting algorithms

Insertion Sort
Insertion Sort algorithm has a simple idea. Assume an array with items to be sorted. We divide the array into two parts: sorted one and unsorted one. At the beginning sorted part consists of the first element (Figure 6). Then, for each item that we have in the unsorted part, we take element and insert it into the right place among the sorted items.

Figure 3: Insertion Sort: sorted and unsorted parts at the beginning

In order to insert element into the right place in the sorted part, we compare selected item from the unsorted part with each item from the sorted part in the direction from right to left. Comparing continues until smaller or equal element is found or no elements to compare left. After each comparison, if current item in the sorted part is greater, we move that current item one position right. Finally, when the right position is found, we insert an item into the sorted part. Complexity of Insertion Sort is Θ(n2).

Selection Sort
Selection Sort algorithm is based on the repeated selection. Here we consider finding minimal key from the unsorted part and swapping it with the first un- sorted key. As well as in the Insertion Sort, sorted part grows from the beginning of the sequence. 
Assume an array of items to sort. At the beginning of the sorting process unsorted part is represented by the whole array. Then, the first item of the unsorted part is set as the smallest item and is compared with the follow-up elements. When smaller item is found, it is set as a new smallest key. After the end of the array is reached the smallest item is swapped with the first element of the unsorted part and it becomes the sorted part of the array. This step is repeated till the array is sorted. Complexity of this sorting algorithm is Θ(n2).
 
Bubble Sort
Bubble Sort is based on the idea of exchanging two adjacent elements if they have the wrong order. The algorithm works stepping through all elements from left to right, so the largest elements tend to move or "bubble" to the right (Figure 4). That is why the algorithm is called Bubble Sort.
Now we are going to the details. Let us have an unsorted array. The algo- rithm does iterations through the unsorted part which is the whole array at the beginning. And with each iteration through the array the range of inspected items is decreased by one till only two elements left. After this two elements are compared and possibly swapped, the array is considered as sorted. Bubble Sort complexity is Θ(n2).

if you want to contact then mail at royraman32@gmail.com

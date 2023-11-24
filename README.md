### ***Date*** : 16-20 November
### ***Title*** : LAB17-Sorting
### ***Aim*** : Sorting Algorithms (Selection sort, Insertion sort, Bubble sort)
### ***Algorithm*** :

Selection Sort:
Start: Begin with the first element of the array.
Find Minimum: Find the smallest element in the unsorted part of the array.
Swap: Swap the found minimum element with the first element of the unsorted part.
Repeat: Repeat the above steps for the remaining unsorted part of the array.
End: The array is sorted when all elements are considered.

Insertion Sort:
Start: Begin with the second element of the array.
Insert: Insert this element into its correct position among the already sorted elements to its left.
Shift: If needed, shift the larger sorted elements to make space for the inserted element.
Repeat: Repeat the above steps for the remaining unsorted part of the array.
End: The array is sorted when all elements are considered.

Bubble Sort:
Start: Begin with the first element of the array.
Compare: Compare the current element with the next element.
Swap: If the current element is greater than the next element, swap them.
Repeat: Repeat steps 2 and 3 for all elements in the array.
One Pass: After one pass, the largest unsorted element is at the end of the array.
Repeat: Repeat steps 2-5 for the remaining unsorted part of the array.
End: The array is sorted when no more swaps are needed.

### ***Explanation*** :

Selection Sort:
Imagine you have a list of numbers. In selection sort, you start by finding the smallest number in the list and putting it at the beginning. Then, you find the next smallest and put it in the second position. You keep doing this until the entire list is sorted.

Insertion Sort:
Think of a deck of cards that you want to arrange. With insertion sort, you pick one card at a time and insert it into its correct place in the already sorted part of the deck. You shift the other cards if needed. Repeat this process until all cards are in order.

Bubble Sort:
Picture a row of bubbles in a glass of soda. In bubble sort, you compare adjacent pairs of numbers in your list. If a pair is in the wrong order, you swap them. This process is like making the larger bubble "rise" to its correct position. You keep bubbling through the list until everything is sorted.

### ***Output Screenshot*** :

Code:

Output:

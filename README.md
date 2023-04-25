# Binary-search

Binary search is a search algorithm that works on a sorted array. It starts by comparing the target value to the middle element of the array. If the target value is less than the middle element, the search continues on the lower half of the array. If the target value is greater than the middle element, the search continues on the upper half of the array. The process repeats until the target value is found or the search range is exhausted.

Here's how binary search works in pseudocode:

Set the left index to 0 and the right index to the last element in the array.
While the left index is less than or equal to the right index:
a. Calculate the middle index as the average of the left and right indices.
b. If the target value is equal to the middle element, return the middle index.
c. If the target value is less than the middle element, set the right index to the middle index minus one.
d. If the target value is greater than the middle element, set the left index to the middle index plus one.
If the target value is not found, return -1.
Here's an example of how binary search works:

Suppose we have the following array: [1, 3, 4, 7, 9, 11, 15, 17, 19, 22]. We want to search for the target value of 11.

Set the left index to 0 and the right index to 9.
The middle index is 4, and the middle element is 9. Since 11 is greater than 9, we set the left index to 5.
The middle index is 7, and the middle element is 17. Since 11 is less than 17, we set the right index to 6.
The middle index is 5, and the middle element is 11. We have found the target value, so we return 5.
In this example, binary search found the target value in three iterations, which is much faster than a linear search that would have taken ten iterations on average.






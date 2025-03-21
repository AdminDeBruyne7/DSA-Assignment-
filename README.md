#**Question 1**
the big O notation helps us understand how an algorithms performance changes as the input size growa. the key rules are:
 **drop constants**: big O notation focuses on how fast the runtime grows, so we ignore the constants e.g. If an algorithm runs in O(2n), we simplify it to O(n) because doubling doesn’t change the overall trend.
 **Drop-non Dominant Terms**: in this rule, when multiple terms exist, we only keep the one that grows faster e.g. If an algorithm runs in O(n² + n), we drop n and just say O(n²) because n² dominates as n grows.
 **Different inputs means Different Variables**: in this rule, if an algorithm has many multiple inputs, they should have seperate teams e.g. If we compare every student in a class with every book in a library, it might take O(m × n) time, where m is the number of students and n is the number of books
 **Worst Case Matters Most**: in this rule big O usually focuses on the worst case scenerio since it guarantees performance limits e.g. For a search in an unsorted list, the best case (first item found) is O(1), but the worst case (last item or not found) is O(n), so we say O(n)
 **Exponential and Factorial Grow the Fastest**: in this rule, the exponential and factorial algorithms grow incredibly fast, making them impractical for large inputs e.g. Solving a puzzle with every possible combination might take O(2ⁿ) time


 #**Question 2**
 **Memory Allocation**: An array has contiguous block of memory, all allocated at once whereas linked lists have a dynamic memory alllocation, each node stored seperately
 **Perfromance**: an array has a faster access for index based lookup, whereas a linked list has a slower access to find an element
 **Insertion and Deletion**: an array is costly, in worst case, shifting is needed whereas linked list is much more efficient at head elsewhere no shifting 

 **Explananation**
 
 **Memory Allocation**
 *Arrays are like train compartments, each is fixed in position, and resizing requires a new train.
Linked lists are like a chain, you can add or remove links without moving the entire chain*

**Perfromance**
*Arrays allow instant access by index (like checking a numbered locker).
Linked lists require traversal, they like searching through a row of lockers one by one*

**Insertion and Deletion**
*Arrays need shifting when inserting/deleting in the middle.
Linked lists just change pointers at the head elsewhere*



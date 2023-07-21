# Algorithm Summary

Refererence
https://github.com/teivah/algodeck/blob/master/array.md
https://www.metacareers.com/profile/preparation_hub

Q: When do you want to use Linked List, Stack, Normal array, Queue?

A: 

* Linked List:

Use linked lists when you need efficient insertion and deletion at arbitrary positions in the list.

Pros:
Dynamic size: Linked lists can easily grow or shrink in size as elements are added or removed.
Efficient insertion and deletion: Insertion and deletion operations can be performed in constant time O(1) at the beginning or end of the list.
Cons:
Random access: Accessing elements by index is not as efficient as in arrays since it requires traversing the list from the beginning.

* Stack:

Use stacks when you need to implement a Last-In-First-Out (LIFO) data structure.
Pros:
Simple interface: Stacks have a straightforward interface with push (add element) and pop (remove element) operations.
Efficient operations: Push and pop operations are constant time O(1).
Cons:
Limited access: Accessing elements in the middle of the stack or by index is not efficient. You can only access the topmost element.

* Normal Array:

Use normal arrays when you need random access to elements or a fixed-size collection of elements.
Pros:
Random access: Elements can be accessed directly by index, allowing efficient random access.
Compact memory representation: Elements are stored in contiguous memory locations.
Cons:
Fixed size: Normal arrays have a fixed size, which means they cannot dynamically grow or shrink.
Costly insertions and deletions: Insertions and deletions in the middle of the array require shifting elements, resulting in a higher time complexity.


* Queue:

Use queues when you need to implement a First-In-First-Out (FIFO) data structure.
Pros:
Enforced order: Queues maintain the order of elements, ensuring that the first element inserted is the first to be removed.
Efficient operations: Enqueue (add element) and dequeue (remove element) operations are constant time O(1).
Cons:
Limited access: Accessing elements in the middle of the queue or by index is not efficient. You can only access the front and rear elements.

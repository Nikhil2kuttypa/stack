# stack
Generic Method Stack
This repository contains a Java implementation of a generic stack data structure along with a demonstration of its usage. The stack implementation (Generic) allows you to store elements of any data type in a stack-like structure.
push(T ele): Adds an element to the stack. If the stack is full, it calls the expand() method to increase the capacity.
size(): Returns the current size of the stack.
expand(): Doubles the capacity of the stack when it's full.
show(): Displays the elements of the stack.
pop(): Removes and returns the top element from the stack. It also calls the shrink() method to reduce the capacity if the size of the stack falls below a certain threshold.
shrink(): Reduces the capacity of the stack if the size falls below a quarter of the capacity.
isEmpty(): Checks if the stack is empty.

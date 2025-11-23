### EX: 10.4  check whether the stack is full and then display the stack values in reverse order
### Aim: Write a Python program to create a stack of maximum size 5 using LifoQueue, accept elements from the user, check whether the stack is full, and then display the elements in reverse order (from top to bottom).

### Algorithm:
Start
Import LifoQueue from the queue module.
Create a stack with a maximum size of 5.
Read the number of elements 𝑛
n to be inserted (up to 5).
For each element (up to 𝑛n):
Read the input number.
Push (put) the element onto the stack.
Check if the stack is full using stack.full().
Print True if full, else False.
Create an empty list to store popped elements.
While the stack is not empty:
Pop (get) an element from the stack and append it to the list.
Print the elements of the list (which represent the stack in reverse order).
End
### Program:
```
reg no:212223070021
name:Ragunandhan S
from queue import LifoQueue
stack = LifoQueue(maxsize=5)
n= int(input())
for i in range(n):
    stack.put(input())
print(stack.full())
for i in range(n):
    print(stack.get())

```
### Output:
![image](https://github.com/user-attachments/assets/51f4d171-f949-4d94-8945-f2f7dd08b203)

### Result: Thus, the given program is implemented and executed successfully .
 



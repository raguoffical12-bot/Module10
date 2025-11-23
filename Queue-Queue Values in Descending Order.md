### EX: 10.2 IMPLEMENTATION OF STACK
### Aim: To Write a python program to implement the stack using deque method for rotating the stack.
### Algorithm:

STEP 1: Start.

STEP 2: Import collections and import deque.

STEP 3: Create a list and get the input from user.

STEP 4: Create a variable n and get number of inputs from user.

STEP 5 : Using a loop get the inputs from user and append in deque.

STEP 6: Using rotate function rotate the stack.

STEP 7 : Print the result. 

STEP 8 : Stop.
### Program: 

```
reg no:212223070021
name:Ragunandhan S
from collections import deque

stack = deque()

n = int(input("Enter number of elements to push into the stack: "))
for _ in range(n):
    val = input("Enter value: ")
    stack.append(val)

print("Original Stack:", list(stack))

k = int(input("Enter rotation value (positive = right, negative = left): "))
stack.rotate(k)

print("Stack after rotation:", list(stack))

```
### Output:

![image](https://github.com/user-attachments/assets/e6fcaef4-4b5c-45b5-a015-b6bcdb9aeb99)

### Result: Thus, the given program is implemented and executed successfully .
 

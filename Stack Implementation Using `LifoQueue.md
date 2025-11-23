EX: 10.3 QUEUE
### Aim: To Write a python program to implement the stack using deque method for rotating the stack.
### Algorithm:

STEP 1: Start.

STEP 2: Import collections and import deque.

STEP 3: Create a stack and a variable n.

STEP 4: Get the number of inputs from user.

STEP 5: Using a loop get the inputs from user.

STEP 6: Append the even and unique elements in the stack.

STEP 7: Print the result.
### Program:
```
reg no:212223070021
name:Ragunandhan S
from collections import deque

class Stack:
    def __init__(self):
        self.stack = deque()

    def push(self, value):
        self.stack.append(value)

    def pop(self):
        if self.is_empty():
            return None
        return self.stack.pop()

    def rotate(self, k):
        self.stack.rotate(k)

    def display(self):
        print("Stack (top on right):", list(self.stack))

    def is_empty(self):
        return len(self.stack) == 0

# Example usage
s = Stack()
n = int(input("Enter number of elements to push into the stack: "))
for _ in range(n):
    val = input("Enter value: ")
    s.push(val)

s.display()

k = int(input("Enter rotation value (positive = right, negative = left): "))
s.rotate(k)

print("After rotation:")
s.display()

```
### Output:
![image](https://github.com/user-attachments/assets/f36727ec-a380-4373-885f-9aee0e398f09)

 
### Result: Thus, the given program is implemented and executed successfully .

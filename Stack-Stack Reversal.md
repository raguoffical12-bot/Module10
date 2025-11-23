# 19CS301-Module10
###EX: 10.a  STACK
### Aim: To Write a python program to get the integer values from the user and push only the odd number into the stack and later pop the last 2 elements
### Algorithm:
STEP 1: Start.

STEP 2: Create a list and a variable n.

STEP 3: Get the value of n from user.

STEP 4: Using loop append only odd elements in the stack.

STEP 5 : Using another loop using built-in pop operation pop the last two elements.

STEP 6: Print the result.

STEP 7 : Stop.
### Program:
```
reg no:212223070021
name:Ragunandhan S
stack = []
n = int(input("Enter the number of elements: "))

for _ in range(n):
    val = int(input())
    if val % 2 != 0:
        stack.append(val)

print("Stack after pushing odd numbers:", stack)

if len(stack) >= 2:
    stack.pop()
    stack.pop()
elif len(stack) == 1:
    stack.pop()

print("Stack after popping last 2 elements:", stack)

```
### Output:
![image](https://github.com/user-attachments/assets/dd8866bf-2d68-4da9-b7b6-c4d2f1b0730c)


### Result: Thus, the given program is implemented and executed successfully .

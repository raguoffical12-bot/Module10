### EX: 10.4 IMPLEMENTATION OF QUEUE
### Aim: To Develop a python program to get the 4 integer values from user and display the values using multiprocessing library
### Algorithm:

STEP 1: Start.

STEP 2: From Multiprocessing Import Queue.

STEP 3: Create a list and get the input from user.

STEP 4 : Append the elements in the list.

STEP 5: Using 'get' built-in function print the list.

STEP 6 : Print the result.

STEP 7 : Stop.
### Program:
```
reg no:212223070021
name:Ragunandhan S
from multiprocessing import Process

def display_value(val):
    print(f"Value: {val}")

if __name__ == "__main__":
    values = []
    print("Enter 4 integer values:")
    for i in range(4):
        num = int(input(f"Value {i+1}: "))
        values.append(num)

    processes = []
    for val in values:
        p = Process(target=display_value, args=(val,))
        processes.append(p)
        p.start()

    for p in processes:
        p.join()

```
### Output:
 ![image](https://github.com/user-attachments/assets/f698ccce-41a4-4d3b-bb21-59ac020aae89)


### Result: Thus, the given program is implemented and executed successfully .
 

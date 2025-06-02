# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 
      from collections import deque
      que = []  
      n=int(input())
      for i in range(n):
          que.append(int(input()))  
      for i in range(2):
          que.pop()
      print(que)
      
   
### Output:
![image](https://github.com/user-attachments/assets/9388a77c-33d3-4610-a743-b08daa48c0c0)


## Result:
Thus, the program that simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending orders is executed and verified successfully.

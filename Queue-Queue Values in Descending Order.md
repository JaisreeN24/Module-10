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
      q = deque()
      n=int(input())
      for i in range(n):
          q.append(input())
      for i in range(2):
          q.popleft()
      print(q)
### Output:
![image](https://github.com/user-attachments/assets/a5f7f8b3-983d-4764-bc9f-5af43fcd8061)

## Result:
Thus, the program that simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending orders is executed and verified successfully.

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
```
## Output

![image](https://github.com/user-attachments/assets/5b91c76a-1e1b-490d-83b1-630257f597ea)

## Result
Thus the program that handles an IndexError when trying to access an element beyond the available range of a list is executed successfully

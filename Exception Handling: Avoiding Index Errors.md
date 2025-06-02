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
msg=[5, 28, 25]
try:
    print(msg[5])
except IndexError:
    print("You're out of list range")
```
## Output
![p15](https://github.com/user-attachments/assets/ed388c80-1b82-46b3-922c-bd24d039d636)

## Result
The program was executed successfully. It correctly handles an IndexError when attempting to access an element beyond the available range of a list, ensuring the program does not crash and provides an appropriate error message.

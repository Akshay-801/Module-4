# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
with open("story.txt", "r") as file:
    count = 0  # Initialize counter
    for line in file:
        if not line.lstrip().startswith('T'):
            count += 1
print("Number of lines that do NOT start with 'T':", count)
```
## Output
![Screenshot 2025-06-02 223021](https://github.com/user-attachments/assets/6dfab5f6-1d89-4b3d-b167-093ecd70393c)

## Result
The program was executed successfully. It correctly reads the file story.txt and counts the number of lines that do not start with the alphabet 'T', displaying the final count as output.



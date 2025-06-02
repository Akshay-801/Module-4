# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d=eval(input())
l=sorted(d.keys())
print('Keys and Values sorted in alphabetical order by the key')
for i in l:
    print((i,d[i]), end=" ")
```

## Sample Output
![p14](https://github.com/user-attachments/assets/f38b60eb-2680-4e1f-a138-e3a10dc28b06)

## Result
The program was executed successfully. It correctly sorts the dictionary's keys in alphabetical order and values in alphabetical order, and displays the sorted results.


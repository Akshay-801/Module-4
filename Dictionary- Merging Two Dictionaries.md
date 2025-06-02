## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
def merge (dict1,dict2): 
   res={**dict1 , **dict2}
   return res 
dict1=eval(input())
dict2=eval(input())
dict3=merge(dict1,dict2) 
print(dict3)
```

## Output
![p13](https://github.com/user-attachments/assets/178e9beb-5de9-4e78-9c9b-04affdda5bbb)

## Result
The program was executed successfully. It correctly merges two dictionaries and combines their key-value pairs into a single dictionary.

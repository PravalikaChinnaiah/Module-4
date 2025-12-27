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
Add Code here
~~~
my_dict = {3: 323, 1: 2, 5: 12, 6: 18, 4: 24, 2: 56}
sorted_items = sorted(my_dict.items(), key=lambda x: x[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
~~~
## Sample Output
<img width="1157" height="321" alt="image" src="https://github.com/user-attachments/assets/5aea6b41-8165-41ab-ae86-bd1ede4b97f4" />


## Result
Thus,the Python program  that sorts a dictionary's is created successfully.

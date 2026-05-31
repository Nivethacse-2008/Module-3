# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

t = tuple(input("Enter tuple elements separated by space: ").split())

if 'n' in t and '8' in t:
    print("Both 'n' and 8 are present")
else:
    print("Either 'n' or 8 is missing")

## Output

<img width="1148" height="223" alt="image" src="https://github.com/user-attachments/assets/077dfcfb-8561-467a-b176-f696d8b217e5" />

## Result
The program successfully checks whether the element 'n' and the number 8 exist in the tuple using the in operator.

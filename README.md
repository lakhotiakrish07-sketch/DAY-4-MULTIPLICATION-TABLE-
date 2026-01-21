# Multiplication Table Generator (Python)

A simple Python program that prints the multiplication table of any number entered by the user.  
This project is beginner-friendly and helps understand **loops**, **user input**, and **string formatting (f-strings)** in Python.

---

## 🚀 Features
- Takes a number as input from the user
- Prints the multiplication table from **0 to 10**
- Uses **for loop**
- Uses **f-string formatting**

---

## 🧠 Concepts Used
- `input()` function
- Type casting (`int`)
- `for` loop
- `range()`
- f-strings for formatting output

---

## 📌 Code
```python
print("give me a number you want to find table of ")
num = int(input("number:"))

for i in range(11):
    print(f"{num}x{i}=", num*i)
💻 Example Output
If user enters 5:

css
Copy code
give me a number you want to find table of 
number: 5
5x0= 0
5x1= 5
5x2= 10
5x3= 15
5x4= 20
5x5= 25
5x6= 30
5x7= 35
5x8= 40
5x9= 45
5x10= 50
📂 How to Run
Make sure Python is installed

Run the program:

bash
Copy code
python table.py
⭐ Author
Made by Krish Lakhotia

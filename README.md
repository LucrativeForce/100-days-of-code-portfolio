# 🐍 100 Days of Code – My Python Journey  

I’m following the 100 Days of Code challenge, but at my own pace.  
Instead of rushing through one project per day, I’m documenting each coding session so I can focus on *understanding deeply before moving on*.  

This means some projects will take multiple sessions (and therefore multiple “days” in my log). That’s perfectly fine — the goal is **consistency and growth, not speed**.  

---

### 📑 Table of Contents

- [September 30, 2025 – Project 1, Part A](#september-30-2025--project-1-part-a)  
- [October 1, 2025 – Project 1, Part B](#october-1-2025--project-1-part-b)  
- [October 6, 2025 – Data Types & Math Operations](#october-6-2025--data-types--math-operations)
- [October 8, 2025 – Tip Calculator Project](#october-8-2025--tip-calculator-project)

---

## September 30, 2025 – Progress Log: Project 1, Part A

### 🌱 What I Learned  
- How to use the `print()` function to display text.  
- Newline characters `\n` to split text across lines.  
- String concatenation (using `+` to join words together).  
- First experience with `input()` to collect user input.  
- First exposure to `len()` to measure the length of input text.  

### 💻 Code I Wrote  
```python
# Printing basics
print("Hello world!")

# String concatenation and new lines
print("Hello\nWorld")
print("Hello" + " " + "Angela")

# First try at input and length
print(len(input("What is your name?")))
```

✅ Sample Output

Hello world!
Hello
World
Hello Angela
What is your name? Angela
6

🪞 Reflection

Today I wrote my very first lines of Python code. Printing text and joining words with + felt simple but exciting — it showed me how code can shape output. I also learned about \n for new lines, which made me realize programming is like giving precise stage directions to the computer. It’s a small start, but it feels powerful.

---

## October 1, 2025 – Progress Log: Project 1, Part B

### 🌱 What I Learned

- How variables store values (labels for data).  
- The role of the assignment operator `=` (left = variable name, right = value).  
- The difference between `"username"` (a literal string) and `username` (a variable).  
- How to use variables with the `len()` function to measure text length.  
- Built my first mini-project: **Band Name Generator.**

💻 Code I Wrote
```python
# PAUSE 1 – One-liner: ask for a name and print its length
print(len(input("What is your name?")))

# PAUSE 2 – Split into variables (learning variables + len)
username = "Angela"
length = len(username)
print(length)

# Project 1 – Band Name Generator (my version today)
print("Band Name Generator")
print("What city did you grow up in?")
city = "Boise"
print(city)

print("What is the name of your first pet?")
pet = "Whiskers"
print(pet)

print("Band Name:")
print(city + " " + pet)
```

✅ Sample Output

What is your name? Angela
6
Band Name Generator
What city did you grow up in?
Boise
What is the name of your first pet?
Whiskers
Band Name:
Boise Whiskers

🪞 Reflection

Today I had my “aha!” moment with variables. I realized that variables are like little storage boxes where I can keep information and reuse it later. At first, I kept confusing the variable name with the string text, but once it clicked, I could see how powerful this is. Writing my first mini-project, the Band Name Generator, made me feel like I was actually coding something real.

---

## October 5, 2025 – Progress Log: Data Types & Math Operations

---

### 🔁 Revisiting Previous Code: Band Name Generator Fix

Today I reviewed and improved my Band Name Generator from earlier in the course.  
I fixed the input spacing issue and improved how the final band name is displayed.

---

### 🧩 Updated Code

```python
# Band Name Generator (Improved)
print("Welcome to the Band Name Generator!")

# Get user input
city = input("What city did you grow up in?\n")
pet = input("What is the name of your pet?\n")

# Combine both inputs with proper spacing
band_name = city + " " + pet

# Display result
print("Your band name could be: " + band_name)
```
---

### 🌱 What I Learned
- The four basic data types in Python:  
  - **String (`str`)** → text inside quotes  
  - **Integer (`int`)** → whole numbers (e.g., `5`, `1234`)  
  - **Float (`float`)** → decimal numbers (e.g., `2.55`)  
  - **Boolean (`bool`)** → `True` or `False` values  
- How to use the `type()` function to check what kind of data something is.  
- How Python raises **TypeErrors** when trying to mix incompatible data types (like adding text and numbers).  
- How to fix a TypeError by converting data types using functions like:  
  - `str()` to turn numbers into text  
  - `int()` to turn text numbers into integers  
  - `float()` to turn text numbers into decimals  
- Learned about **PEMDAS** order of operations in math expressions:  
  **Parentheses → Exponents → Multiplication/Division → Addition/Subtraction.**

---

### 🧩 Code I Wrote

```python
# Checking different data types
print(type("Hello"))   # String
print(type(1234))      # Integer
print(type(2.55))      # Float
print(type(True))      # Boolean

# Fixing a TypeError with type conversion
print("Number of letters in your name: " + str(len(input("Enter your name: "))))

# Mathematical operations (PEMDAS practice)
# Original version
# print(3 * 3 + 3 / 3 - 3)

# Adjusted version to make it output 3
print(3 * (3 + 3) // 3 - 3)
```

🧠 Sample Output

<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>

Enter your name: Mandi
Number of letters in your name: 5

3

💬 Reflection

Today I really started understanding data types — and how Python sees numbers and text differently.
I learned how to fix TypeErrors, use type conversions, and even practiced math order (PEMDAS).
It’s starting to click how everything fits together — the logic, the structure, and the patterns in the code.
Feeling proud of today’s progress. 🙌

---

---

## 🐍 October 8, 2025 – Tip Calculator Project  

### 🌱 What I Learned  
- How to combine user input with math operations.  
- How to convert strings into floats and integers using `float()` and `int()`.  
- How to calculate percentages and split totals evenly.  
- How to use `round()` to control decimal places.  
- The difference between a single-line solution and a step-by-step version for readability.  
- Reinforced how assignment operators and variable naming make code more organized and logical.  

---

### 💻 Code I Wrote – My Own Version  
```python
print("Welcome to the tip calculator!")

bill = float(input("What was the total bill? $"))
tip = int(input("What percentage tip would you like to give? 10 12 15 "))
people = int(input("How many people to split the bill? "))

print(f"Each person should pay: ${round((bill * (1 + tip / 100)) / people, 2)}")
```
💡 Instructor Version (Broken Down Step by Step)
```
print("Welcome to the tip calculator!")

bill = float(input("What was the total bill? $"))
tip = int(input("What percentage tip would you like to give? 10, 12, or 15? "))
people = int(input("How many people to split the bill? "))

tip_as_percent = tip / 100
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = round(bill_per_person, 2)

print(f"Each person should pay: ${final_amount}")
```
🧮 Sample Output
```
Welcome to the tip calculator!
What was the total bill? $150
What percentage tip would you like to give? 10 12 15 12
How many people to split the bill? 5
Each person should pay: $33.60
```
✨ Reflection

Today I completed the Tip Calculator Project, and it really clicked how important parentheses and logic order are.
I learned that writing shorter code is fun and powerful, but breaking it down step by step makes it easier to understand and maintain.
It was rewarding to figure out the formula on my own before watching the instructor’s deeper breakdown — that showed me I’m actually learning to think like a programmer.

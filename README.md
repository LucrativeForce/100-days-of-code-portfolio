# 🐍 100 Days of Code – My Python Journey  

I’m following the 100 Days of Code challenge, but at my own pace.  
Instead of rushing through one project per day, I’m documenting each coding session so I can focus on *understanding deeply before moving on*.  

This means some projects will take multiple sessions (and therefore multiple “days” in my log). That’s perfectly fine — the goal is **consistency and growth, not speed**.  

---

## 📑 Table of Contents  
- [Day 1 – September 30, 2025 (Project 1, Part A)](#day-1--september-30-2025-project-1-part-a)  
- [Day 2 – October 1, 2025 (Project 1, Part B)](#day-2--october-1-2025-project-1-part-b)  

---

## Day 1 – September 30, 2025 (Project 1, Part A)  

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

Day 2 – October 1, 2025 (Project 1, Part B)

🌱 What I Learned
	•	How variables store values (labels for data).
	•	The role of the assignment operator = (left = variable name, right = value).
	•	The difference between "username" (a literal string) and username (a variable).
	•	How to use variables with the len() function to measure text length.
	•	Built my first mini-project: Band Name Generator.

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

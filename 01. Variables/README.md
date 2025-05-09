<p align="center">
  <img src="https://github.com/jeevan499/Python/blob/jeevanrajraj1998%40gmail.com/01.%20Variables/variables.jpg" alt="SQL Banner" />
</p>

# 📌 Variable Assignment in Python

Welcome to the **Variable Assignment in Python** section of the Python Learning Repository!  
This module covers the fundamentals of declaring, assigning, and managing variables in Python. It is designed for beginners and intermediate learners to understand how Python handles variables and to adopt best practices for clean and efficient coding.

---

## 📚 Overview

Variables in Python are used to store data that can be referenced and manipulated throughout a program. Python's dynamic typing allows variables to be assigned without explicitly declaring their type, making it flexible but requiring careful naming and usage to avoid errors.

### Key Concepts
- **Variable Declaration and Assignment**: Assign values using the `=` operator.
- **Naming Conventions**: Follow rules and best practices for readable variable names.
- **Dynamic Typing**: Variables can change types during execution.
- **Scope**: Understand where variables are accessible (local vs. global).
- **Multiple Assignment**: Assign values to multiple variables in a single line.

---

## 📝 Content

### 1. Basic Variable Assignment
Learn how to:
- Assign values to variables using `=`.
- Reassign values to existing variables.
- Example:
  ```python
  name = "Alice"
  age = 25
  age = 26  # Reassignment
  ```

### 2. Variable Naming Rules
Understand Python's naming conventions:
- Names must start with a letter or underscore (`_`).
- Names can contain letters, numbers, and underscores.
- Names are case-sensitive (`age` ≠ `Age`).
- Avoid reserved keywords (e.g., `if`, `for`, `while`).
- Example:
  ```python
  first_name = "Bob"  # Valid
  _count = 10         # Valid
  2nd_place = 5       # Invalid
  ```

### 3. Dynamic Typing
Explore how Python allows variables to change types:
- Example:
  ```python
  x = 10      # x is an integer
  x = "Hello" # x is now a string
  ```

### 4. Multiple Assignment
Assign multiple variables in one line:
- Example:
  ```python
  a, b, c = 1, 2, 3
  x = y = z = 0  # Assign same value to multiple variables
  ```

### 5. Variable Scope
Understand local and global variables:
- Local: Defined inside a function, accessible only within it.
- Global: Defined outside functions, accessible everywhere.
- Example:
  ```python
  global_var = "I'm global"
  def my_function():
      local_var = "I'm local"
      print(global_var)  # Accessible
      print(local_var)   # Accessible
  print(local_var)       # Error: local_var is not defined
  ```

### 6. Best Practices
- Use meaningful variable names (e.g., `total_price` instead of `tp`).
- Follow PEP 8 naming conventions (lowercase with underscores for variables).
- Avoid single-letter names except for counters (e.g., `i` in loops).
- Use constants in uppercase for values that don’t change (e.g., `MAX_SIZE = 100`).

---

## ⚙️ Tools & Technologies Used

- **Programming Language**: Python 3.x  
- **IDE**: VS Code / PyCharm / Jupyter Notebook  
- **Practice Platforms**: LeetCode, HackerRank *(optional)*  

---

## 🏁 Getting Started

1. Clone the repo:
    ```bash
    git clone https://github.com/your-username/Python-Learning-Resources.git
    cd Python-Learning-Resources/Variable-Assignment
    ```
2. Open the `.py` files or Jupyter notebooks in your preferred IDE.
3. Run the example scripts to experiment with variable assignments.

---

## 🛠️ Example Code
Here’s a sample script to demonstrate variable assignment concepts:
```python
# Basic assignment
name = "Alice"
age = 30

# Multiple assignment
x, y = 10, 20

# Dynamic typing
value = 42
value = "Python"

# Scope
global_message = "Hello, World!"
def greet():
    local_message = "Hi there!"
    print(global_message)  # Outputs: Hello, World!
    print(local_message)   # Outputs: Hi there!

greet()

# Naming conventions
total_price = 99.99
MAX_USERS = 100  # Constant
```

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to:
- Add more examples or exercises
- Improve explanations
- Suggest additional topics

Just fork the repo and submit a pull request. Let's learn together! 🚀
Explore the full Python file here 👉 [Variables Assignments in Python](https://github.com/jeevan499/Python/blob/jeevanrajraj1998%40gmail.com/01.%20Variables/01-Variable%20Assignment.ipynb)


---

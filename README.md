# Python Syntax Checker Tool

## 📌 Project Title
Python Syntax Checker Tool

## 📝 Problem Statement
Beginner programmers often face difficulty identifying syntax errors in Python scripts. Manually finding such errors can be time-consuming and frustrating. A lightweight tool to check syntax without executing the code will help learners validate their scripts quickly.

**Question:**  
How can we develop a Python tool that reads another Python script and identifies any syntax errors without running the program?

## 🎯 Objective
The tool checks a Python script for syntax errors using Python's built-in `compile()` function, without executing the code.

## 🚀 Features
- Accepts a Python file as input  
- Reads file content using file handling  
- Validates syntax using `compile()`  
- Catches errors with `try-except`  
- Displays clear error messages with line number  

## ⚙️ Functional Components
1. File input through user prompt or upload  
2. Read and store script content  
3. Validate syntax using `compile()`  
4. Catch syntax errors and display error message  
5. Show "No Errors" if the script is valid  

## 📂 Project Structure

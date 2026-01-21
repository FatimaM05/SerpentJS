# 🐍 SerpentJS  
### Python → JavaScript Transpiler

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript&logoColor=black)
![Compiler](https://img.shields.io/badge/Category-Transpiler-purple)
![Architecture](https://img.shields.io/badge/Architecture-Compiler%20Pipeline-orange)
![Status](https://img.shields.io/badge/Status-Experimental%20%7C%20Academic-red)

> **Write Python. Run JavaScript.**

**SerpentJS** is a modern **Python → JavaScript transpiler** built from scratch using compiler construction principles.  
It converts a well-defined subset of Python into clean, readable, and executable JavaScript while preserving program structure and logic.

This project follows a **full compiler pipeline** — lexical analysis, parsing, semantic analysis, optimization, and code generation — without using parser generators or external compiler frameworks.

---

## 📚 Table of Contents
- [Overview](#-overview)
- [Project Goals](#-project-goals)
- [Supported Features](#-supported-features)
- [Key Algorithms & Techniques](#-key-algorithms--techniques)
- [AST Visualization](#-ast-visualization)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)

---

## 🧠 Overview

SerpentJS bridges Python’s expressive syntax with JavaScript’s runtime ecosystem.  
It allows developers and students to reuse Python logic in JavaScript environments and understand how real-world compilers and transpilers work internally.

The transpiler is **modular, extensible, and educational**, making it suitable for:
- Compiler construction learning
- Language translation experiments
- Cross-platform logic reuse

---

## 🎯 Project Goals

- Build a Python-to-JavaScript transpiler from scratch
- Support core Python language constructs
- Preserve logic and execution behavior
- Provide clear grammar mapping
- Implement robust error handling and reporting
- Generate clean and optimized JavaScript code

---

## ✅ Supported Features

### Language Constructs
- **Functions** (definition & calls)
- **Control Flow**
  - `if / elif / else`
  - `while`
  - `for ... in ...`
- **Assignments** (single variable)
- **Expressions**
  - Arithmetic
  - Comparison
  - Logical
  - Unary
  - Grouping
- **Literals**
  - Integers
  - Floats
  - Strings
  - Booleans
  - `None`

### Keywords
`def`, `return`, `if`, `elif`, `else`, `while`, `for`, `in`, `True`, `False`, `None`

### Operators
`+  -  *  /  %  **  ==  !=  <  >  <=  >=  and  or  not`

---

Each phase is implemented independently to ensure clarity, maintainability, and extensibility.

---

## ⚙ Key Algorithms & Techniques

### 🔹 Lexical Analysis
- Manual tokenization using regular expressions
- Indentation tracking via INDENT / DEDENT tokens
- Line and column–based error reporting

### 🔹 Syntax Analysis
- Recursive Descent Parsing
- Operator precedence handling
- AST construction using structured node classes

### 🔹 Semantic Analysis
- Symbol table with nested scopes
- Type inference and validation
- Detection of undeclared identifiers
- Protection of built-in names

### 🔹 Optimization
- Constant folding
- Dead code elimination
- Expression simplification
- Scope-aware transformations

### 🔹 Code Generation
- Post-order AST traversal
- Python → JavaScript syntax mapping
- Automatic variable declaration tracking
- ES6+ compatible output

---

## 🌳 AST Visualization

SerpentJS supports AST visualization for debugging and learning:
- Console-based AST printing
- **Graphviz** integration for graphical AST rendering

---

## 🧰 Technologies Used

- **Python 3.x** – Core implementation language
- **JavaScript (ES6+)** – Target output language
- **Graphviz** – AST visualization
- **Git & GitHub** – Version control
- **VS Code** – Development environment
- **Jupyter Notebook** – Testing & demonstrations

---

## 📦 Installation

```bash
git clone https://github.com/FatimaM05/SerpentJS.git


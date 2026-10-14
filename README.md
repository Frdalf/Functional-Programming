# 🚀 Functional Programming Laboratory

This repository contains practical assignments, codelabs, and learning modules for the **Functional Programming Practical Course** (Semester 5).

---

## 👤 Student Information

| Information | Details |
| :--- | :--- |
| **Full Name** | Farid Al Farizi |
| **Student ID (NIM)** | 202410370110017 |
| **Course** | Functional Programming Practical Lab |
| **Semester** | 5 |

---

## 📁 Repository Structure

```text
.
├── Codelab 1/
│   ├── MODUL_1_FUNGSIO_26.ipynb      # Module 1 guide and practical reference
│   └── codelab1.ipynb                 # Codelab 1 exercises implementation (Exercises 1–8)
│
├── Codelab 2/
│   ├── MODUL_2_FUNGSIO_26.ipynb      # Module 2 guide and practical reference
│   └── codelab2.ipynb                 # Codelab 2 exercises implementation (Exercises 1–6)
│
├── Tugas 1/
│   ├── Assignment 1/
│   │   └── Assignment_1.ipynb         # Assignment 1: Dual Output, Tuple Conversion, Recursion & Exceptions
│   └── Assignment 2/
│       └── Assignment_2.ipynb         # Assignment 2: Internet Speed Experiment Logging System
│
├── .gitignore                         # Git ignore configurations (Python, macOS, Jupyter)
├── requirements.txt                   # Environment dependencies for Jupyter
└── README.md                          # Repository documentation
```

---

## 📚 Curriculum & Assignment Breakdown

### 🔹 Module 1 & Codelab 1: Python Fundamentals for Functional Programming
- **Core Topics:**
  - Primitive data types, variable scope, immutability vs mutability.
  - Python data structures: Lists, Tuples, Dictionaries, and Sets.
  - Slicing, indexing, and control flow.
  - Basic function concepts, dual-output functions, basic recursion, and exception handling (`try-except`).
- **Codelab 1:** Hands-on solutions for Exercises 1 through 8.

### 🔹 Module 2 & Codelab 2: Pure Functions & Immutability
- **Core Topics:**
  - **Effect-Free Programming:** Writing predictable code free from external side-effects.
  - **Pure Functions:** Deterministic functions producing identical output for identical inputs without mutating outside state.
  - **Immutability:** Safeguarding data states using defensive copies (`copy.deepcopy`) and functional transformations instead of in-place mutation.
- **Codelab 2:** Practical implementations of pure functions and immutable data handling (Exercises 1 through 6).

### 🔹 Assignment 1 & 2
- **Assignment 1:**
  1. *Function 1 & Function 2:* Multi-return data classification functions.
  2. *Tuple Conversion:* Data extraction and immutable tuple conversion for passing students (tailored to odd NIM).
  3. *Recursion with Error Handling:* Recursive traversal and validation combined with `try-except-else` error handling.
- **Assignment 2 (Internet Speed Experiment Logging System):**
  1. *Data Architecture & Mock Data:* Comprehensive mock dataset for network speed benchmarks.
  2. *Input Validation:* Interactive input validation utilizing `while` loops and exception catching.
  3. *Menu Navigation with Slicing:* Modular display formatting via slicing.
  4. *Authentication System:* User registration, login verification, and role-based metadata access.
  5. *Session Lock & Safe Mutation:* Lock mechanism ensuring session security during data mutation.
  6. *Interactive Main Application:* Fully integrated terminal-driven user experience.

---

## 🛠️ Prerequisites & Getting Started

### 1. Requirements
- **Python 3.10+**
- Visual Studio Code (with Jupyter extension) or **JupyterLab** / **Google Colab**

### 2. Virtual Environment Setup (Recommended)
```bash
# Create a virtual environment
python3 -m venv venv

# Activate on macOS / Linux
source venv/bin/activate

# Or activate on Windows (PowerShell)
# .\venv\Scripts\Activate.ps1
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook / Lab
```bash
jupyter lab
# or
jupyter notebook
```
Open any `.ipynb` file in your preferred environment to view or run the code cells.

---

## 📄 Academic Disclaimer & License
This repository is developed strictly for academic coursework in the Functional Programming Practical Course. Feel free to reference it for learning and educational purposes.

EN | [中文](docs/CN.md)

<h1 align="center">Python 🐍 from Zero to OOP 🚀</h1>
<p align="center">A friendly, hands-on path to learn Python from scratch and build solid Object-Oriented Programming (OOP) skills. Made for the Astral Family organization.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Style-Learn--by--Doing-green.svg" alt="Learning Style">
  <img src="https://img.shields.io/badge/Focus-Core_&_OOP-purple.svg" alt="Course Focus">
</p>

---

## 🧭 Table of Contents
- [✨ What You’ll Learn](#-what-youll-learn)
- [🎯 How This Course is Different](#-how-this-course-is-different)
- [👥 Who This Is For](#-who-this-is-for)
- [✅ Prerequisites](#-prerequisites)
- [🛠️ Setup](#️-setup)
- [📚 Curriculum Overview](#-curriculum-overview)
- [🔎 Detailed Syllabus](#-detailed-syllabus)
- [🏗️ Practice Projects](#️-practice-projects)
- [🌱 Next Steps (Optional)](#-next-steps-optional)
- [🔗 Helpful Resources](#-helpful-resources)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ What You’ll Learn
By the end of this course, you will be able to:
- **Write clean, readable Python code** following professional standards.
- **Master fundamental data structures** like lists, dictionaries, sets, and tuples.
- **Control program flow** with conditions, loops, and elegant comprehensions.
- **Organize your code** into functions, modules, and simple packages.
- **Work with files** to read and write data in common formats like CSV and JSON.
- **Handle errors gracefully** and add logging to debug your applications.
- **Design and build your own classes** using Object-Oriented Programming (OOP) principles to model real-world concepts.

This course is laser-focused on core Python and OOP. We do **not** cover web frameworks, APIs, or databases.

---

## 🎯 How This Course is Different
- **Hands-On & Project-Based**: You learn by doing. Every module includes practical exercises and builds towards small, real-world projects.
- **Incremental Steps**: We break down complex topics into small, manageable steps to ensure you build a strong foundation without feeling overwhelmed.
- **Code Quality Focus**: From day one, you'll learn to write code that is not only functional but also clean, well-documented, and easy for others to read.
- **GitHub Workflow**: You will learn and use the standard developer workflow of branching, committing, and creating Pull Requests, preparing you for real-world collaboration.

---

## 👥 Who This Is For
- **Absolute Beginners** with no prior coding experience.
- **Hobbyist Programmers** who know some Python basics but want a structured path to master OOP.
- **Mentors** who are guiding a small group of learners and want a ready-made curriculum with clear checkpoints.

**Suggested pace:** 6–10 weeks, studying part-time.

---

## ✅ Prerequisites
- A computer with an internet connection.
- A GitHub account.
- Basic familiarity with the command line is helpful, but not required (we’ll guide you through the essentials).

---

## 🛠️ Setup
Follow the instructions in **[Module 0: Onboarding & Tools](module%200/README.md)** to set up your complete development environment. The essentials are:

1.  **Install Python 3.12+**
    - Windows: Install from [python.org](https://www.python.org/downloads/) (ensure you check “Add Python to PATH”).
    - macOS: `brew install python@3.12`
    - Linux: Use your system's package manager or `pyenv`.

2.  **Create and activate a virtual environment**
    ```bash
    # Create the environment
    python -m venv .venv
    
    # Activate it (example for macOS/Linux)
    source .venv/bin/activate
    
    # Upgrade pip
    pip install -U pip
    ```

3.  **Recommended Tools**
    - **Editor**: VS Code with the official Python extension.
    - **Version Control**: Git and a GitHub account.

---

## 📚 Curriculum Overview
The course is divided into 9 core modules, designed to take you from zero to confidently building object-oriented programs.

|No | Module | Focus |
|---|--------|-------|
| 0 | Onboarding & Tools ⚙️ | Shell, Git, Python install, venv, VS Code |
| 1 | Python Basics I 🧱 | Syntax, variables, numbers, strings, input/output |
| 2 | Control Flow 🔁 | if/elif/else, match, loops, comprehensions |
| 3 | Data Structures 🧺 | str, list, tuple, set, dict, slicing, mutability |
| 4 | Functions & Types 🧩 | def, args, returns, docstrings, type hints |
| 5 | Modules & Packages 🗂️ | imports, layout, main entry, simple project setup |
| 6 | Files & Data 💾 | pathlib, with, CSV/JSON read/write, simple errors |
| 7 | Errors & Logging 🧯 | exceptions, custom errors, logging basics |
| 8 | OOP & Dataclasses 🏷️ | classes, methods, properties, dataclasses, basics of design |

After completing the core modules, you will apply your skills in a series of practice projects.

---

## 🔎 Detailed Syllabus

<details>
  <summary><strong>Module 0 — Onboarding & Tools ⚙️</strong></summary>
  
  - **Learn**: Command line basics, the complete Git/GitHub workflow (clone, branch, commit, push, PR), Python installation, virtual environments, and VS Code setup.
  - **Build**: Get the repository running on your local machine, write a "Hello, world!" script, and submit your first Pull Request.
</details>

<details>
  <summary><strong>Module 1 — Python Basics I 🧱</strong></summary>
  
  - **Learn**: Core syntax, variables, data types (`int`, `float`, `bool`, `str`), mathematical operations, f-strings for formatting, and user input/output (`input()`, `print()`).
  - **Build**: A tiny calculator, a unit converter, and a string formatting script.
</details>

<details>
  <summary><strong>Module 2 — Control Flow 🔁</strong></summary>
  
  - **Learn**: Conditional logic (`if`/`elif`/`else`), the `match` statement, loops (`for`/`while`), loop control (`break`/`continue`), and list/dictionary/set comprehensions.
  - **Build**: A FizzBuzz-style program, a script for text statistics, and a simple rule engine using `match`.
</details>

<details>
  <summary><strong>Module 3 — Data Structures 🧺</strong></summary>
  
  - **Learn**: In-depth work with strings, lists, tuples, sets, and dictionaries. Covers slicing, indexing, and the crucial concept of mutability vs. immutability.
  - **Build**: A word counter, an anagram checker, and a simple phonebook using dictionary methods.
</details>

<details>
  <summary><strong>Module 4 — Functions & Types 🧩</strong></summary>
  
  - **Learn**: Defining functions (`def`), handling arguments (`*args`, `**kwargs`), return values, writing docstrings, and using type hints for clarity.
  - **Build**: A small library of utility functions with clear documentation and type hints.
</details>

<details>
  <summary><strong>Module 5 — Modules & Packages 🗂️</strong></summary>
  
  - **Learn**: How to use `import`, structure a project into multiple files, use the `__name__ == "__main__"` entry point, and understand relative vs. absolute imports.
  - **Build**: A mini-project split into multiple files with a clear `main.py` starting point.
</details>

<details>
  <summary><strong>Module 6 — Files & Data 💾</strong></summary>
  
  - **Learn**: Using `pathlib` for modern file path manipulation, context managers (`with`), reading/writing text files, and handling structured data with CSV and JSON.
  - **Build**: A command-line tool that converts data from a CSV file to a JSON file with simple validation.
</details>

<details>
  <summary><strong>Module 7 — Errors & Logging 🧯</strong></summary>
  
  - **Learn**: Handling exceptions with `try`/`except`/`else`/`finally`, raising custom errors, and using the `logging` module to record application events.
  - **Build**: Refactor a previous project to include robust error handling and informative log messages.
</details>

<details>
  <summary><strong>Module 8 — OOP & Dataclasses 🏷️</strong></summary>
  
  - **Learn**: The principles of Object-Oriented Programming. Covers classes, `__init__`, methods, properties, and the convenient `@dataclass` decorator.
  - **Build**: A small application that models a real-world domain (e.g., a Library, Bank, or Inventory) using classes and dataclasses.
</details>

---

## 🏗️ Practice Projects
After completing the core modules, choose 2-3 of these projects to build your portfolio.

1.  **Task Tracker CLI** 📝
    - **Description**: A command-line tool to add, list, and mark tasks as complete. Data is saved to a JSON file.
    - **Concepts**: Dictionaries, lists, file I/O (JSON), functions, simple error handling.

2.  **Expense Splitter** 💸
    - **Description**: A tool to split a restaurant bill among several people, including tax and tip. The results can be exported to a CSV file.
    - **Concepts**: Functions, type hints, string formatting, file I/O (CSV).

3.  **Flashcards Trainer** 🎴
    - **Description**: A terminal-based flashcard application that loads questions and answers from a CSV file, quizzes the user, and tracks their score.
    - **Concepts**: Loops, file I/O, modular layout.

4.  **Library Inventory (OOP)** 📚
    - **Description**: A system to manage a library's inventory. Model `Book`, `Member`, and `Loan` with classes. Implement rules for borrowing and returning.
    - **Concepts**: OOP, dataclasses, error handling, logging.

---

## 🌱 Next Steps (Optional)
Once you've mastered OOP, you can explore these intermediate topics:
- **Testing**: Learn the basics of writing tests for your code with `pytest`. 🧪
- **Code Style**: Enforce consistent code style automatically with `Black` and `Ruff`. 🧼
- **Packaging**: Learn to package your project using `pyproject.toml`. 📦
- **GUIs**: Create simple graphical user interfaces with libraries like `Tkinter`. 🪟

---

## 🔗 Helpful Resources
- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [Python Official Documentation](https://docs.python.org/3/)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- [Real Python](https://realpython.com/)
- [PEP 8 (Style Guide)](https://peps.python.org/pep-0008/)

---

## 🤝 Contributing
- Have an idea or find a bug? Open an issue.
- Follow the standard Git workflow: create a branch for each module or feature.
- Always test your code and self-review before opening a Pull Request.
- Engage in feedback to improve your code.

---

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/Astral-Family/Python-Basics/blob/main/LICENSE) file for details.

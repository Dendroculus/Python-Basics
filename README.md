# Python 🐍 from Zero to OOP 🚀
A friendly, hands‑on path to learn Python from scratch and reach solid Object‑Oriented Programming (OOP) skills. Made for the Astral Family organization.

- Python version: 3.12+
- Style: learn by doing, small steps, real mini‑projects
- Goal: master the basics → OOP (no backend yet)

---

## Table of Contents
- [What You’ll Learn ✨](#what-youll-learn-)
- [Who This Is For 👥](#who-this-is-for-)
- [How To Use This Repo 🧭](#how-to-use-this-repo-)
- [Prerequisites ✅](#prerequisites-)
- [Setup 🛠️](#setup-️)
- [Curriculum Overview 📚](#curriculum-overview-)
- [Detailed Syllabus 🔎](#detailed-syllabus-)
- [Checkpoints 🎯](#checkpoints-)
- [Practice Projects 🏗️](#practice-projects-)
- [Next Steps (Optional) 🌱](#next-steps-optional-)
- [Helpful Resources 🔗](#helpful-resources-)
- [Contributing 🤝](#contributing-)
- [License 📄](#license-)

---

## What You’ll Learn ✨
By the end, you will be able to:
- Write clear Python code with good names, comments, and simple tests.
- Work with numbers, strings, lists, sets, and dictionaries.
- Use conditions, loops, and list/dict comprehensions.
- Organize code into functions, files, and small packages.
- Read and write files (CSV/JSON) safely.
- Handle errors and add logs to see what your code is doing.
- Design classes and use dataclasses to model real‑world things.

No web, APIs, or databases here — we stop at OOP.

---

## Who This Is For 👥
- Total beginners (no coding needed).
- Learners who know a bit of Python and want to get strong up to OOP.
- Mentors teaching 1–5 learners with GitHub.

Suggested pace: 6–10 weeks part‑time.

---

## How To Use This Repo 🧭
- Each module has goals and practice tasks.
- Learner workflow:
  1) Make a branch for the module.  
  2) Do the tasks and try the stretch ideas if you can.  
  3) Open a Pull Request (PR) and get feedback.  
  4) Merge when you’re happy with it.

Tip: Turn on branch protection and basic CI (tests + lint) so PRs run checks.

---

## Prerequisites ✅
- A computer with internet
- A GitHub account
- Basic command line helps (we’ll show what you need)

---

## Setup 🛠️
1) Install Python 3.12+
- Windows: install from [python.org](https://www.python.org/downloads/) (check “Add Python to PATH”)
- macOS: `brew install python@3.12`
- Linux: use your package manager or [pyenv](https://github.com/pyenv/pyenv)

2) Make and activate a virtual environment
```bash
python -m venv .venv
# Windows (PowerShell)
. .venv/Scripts/Activate.ps1
# macOS/Linux
source .venv/bin/activate

pip install -U pip
```

3) Nice to have
- VS Code + Python, Pylance, Black, Ruff
- Git + GitHub sign‑in
- Optional: Dev Containers or Codespaces

---

## Curriculum Overview 📚
Core path (9 modules):

| # | Module | Focus |
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

Then: practice projects and optional “next steps” (not backend).

---

## Detailed Syllabus 🔎

### Module 0 — Onboarding & Tools ⚙️
- Learn: command line, Git/GitHub flow, Python install, virtualenvs, VS Code.
- Build: make this repo work locally; “Hello, world!”; first PR.
- Try: change the README, open a PR, ask for review.

### Module 1 — Python Basics I 🧱
- Learn: variables, data types (int/float/bool/str), math, f‑strings, input/output, REPL.
- Build: tiny calculator, unit converter, string formatter.
- Try: format a table of items and prices with f‑strings.

### Module 2 — Control Flow 🔁
- Learn: if/elif/else, `match`, `for`/`while`, `break`/`continue`, list/dict/set comprehensions.
- Build: fizzbuzz+, text stats, simple rule engine with `match`.
- Try: make a number guessing game.

### Module 3 — Data Structures 🧺
- Learn: strings, lists, tuples, sets, dicts; slicing; copying vs mutability.
- Build: word counter, anagram checker, phonebook with dict methods.
- Try: frequency map of letters/words from a file.

### Module 4 — Functions & Types 🧩
- Learn: `def`, returns, default args, `*args`/`**kwargs`, docstrings, type hints.
- Build: small utilities library; add helpful type hints.
- Try: write a tiny “stats” module with clear function names.

### Module 5 — Modules & Packages 🗂️
- Learn: imports, package layout, `__name__ == "__main__"`, relative vs absolute imports.
- Build: mini multi‑file project with a `main.py` entry point.
- Try: split code into `core/` and `cli/` modules.

### Module 6 — Files & Data 💾
- Learn: `pathlib`, context managers (`with`), text vs binary, CSV and JSON.
- Build: CSV ➜ JSON converter with simple validation.
- Try: scan a folder and summarize file sizes and types.

### Module 7 — Errors & Logging 🧯
- Learn: try/except/else/finally, raising your own errors, logging levels/handlers.
- Build: add strong error handling and logs to a previous project.
- Try: write a tiny `validate_input()` that raises clear errors.

### Module 8 — OOP & Dataclasses 🏷️
- Learn: classes, `__init__`, instance/class/static methods, properties, `@dataclass`; when to use composition vs simple data.
- Build: model a small domain (Library/Bank/Inventory) with classes and dataclasses.
- Try: write unit tests for one class (basic happy path and one error case).

---

## Checkpoints 🎯
- C1 (after 0–3): Fundamentals mini‑project (use lists/dicts and loops)
- C2 (after 4–6): Utility project split across modules; reads/writes files
- C3 (after 7–8): OOP project with classes, dataclasses, and error handling

Simple grading idea:
- Correctness 40% (works, handles edge cases)
- Code Quality 30% (readable names, small functions, comments)
- Structure 20% (files/modules make sense)
- Docs 10% (README and usage examples)

Keep finished work in a `portfolio/` folder.

---

## Practice Projects 🏗️
Pick 2–3. Keep them small and polished.

1) Task Tracker CLI 📝  
- Add tasks, mark done, list by status. Save to JSON.  
- Uses: dict/list ops, files, simple errors.

2) Expense Splitter 💸  
- Split a bill between people, handle tax/tip, export CSV.  
- Uses: functions, types, formatting, files.

3) Flashcards Trainer 🎴  
- Load Q&A from CSV, quiz in the terminal, track score.  
- Uses: loops, files, small module layout.

4) Library Inventory (OOP) 📚  
- Book, Member, Loan classes; borrow/return with rules; save JSON.  
- Uses: OOP, dataclasses, error handling, logging.

5) File Organizer 🗂️  
- Move files into folders by type/date; dry‑run mode.  
- Uses: pathlib, functions, logs.

---

## Next Steps (Optional) 🌱
When you’re ready (still no backend), try:
- Testing basics with pytest 🧪
- Code style: Black + Ruff 🧼
- Simple packaging with `pyproject.toml` 📦
- Small GUIs (e.g., Tkinter) 🪟
- Algorithms and problem practice 🧠

---

## Helpful Resources 🔗
- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [Python Official Documentation](https://docs.python.org/3/)
- [Automate the Boring Stuff](https://automatetheboringstuff.com/)
- [Real Python (articles)](https://realpython.com/)
- [PEP 8 (style guide)](https://peps.python.org/pep-0008/)
- [PEP 257 (docstrings)](https://peps.python.org/pep-0257/)

---

## Contributing 🤝
- Open an issue for ideas or bugs.  
- Make a branch per module or feature.  
- Run your code and self‑review before opening a PR.  
- Ask for feedback and improve your PR.

---

## License 📄
MIT LICENSE, see [LICENSE](https://github.com/Astral-Family/Python-Basics/blob/main/LICENSE) for more.

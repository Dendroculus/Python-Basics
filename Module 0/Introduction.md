<h1 align="center">🚀 Module 0: Welcome & Setup ⚙️</h1>
<p align="center">Your journey starts here! In this module, you’ll get your developer toolkit ready and make your first contribution. You’ve got this! 💪</p>

<p align="center">
  <strong>Estimated time:</strong> 60–90 minutes
</p>

---

### 🗺️ Table of Contents
- [🎯 Our Goals for This Module](#-our-goals-for-this-module)
- [🛠️ What You’ll Set Up](#-what-youll-set-up)
- [✅ Before You Start](#-before-you-start)
- [Step 1: Install Python 🐍](#step-1-install-python-312)
- [Step 2: Install Git 🔧](#step-2-install-git)
- [Step 3: Install VS Code 📝](#step-3-install-vs-code)
- [Step 4: Create a Virtual Environment 📦](#step-4-create-a-virtual-environment-)
- [Step 5: Write Your First Script ✨](#step-5-write-your-first-script-)
- [Step 6: The Git & GitHub Workflow 🔄](#step-6-the-git--github-workflow-)
- [Optional: Cloud Setups ☁️](#optional-dev-containers--codespaces)
- [📝 Your Onboarding Checklist](#-your-onboarding-checklist)
- [🏁 Done When...](#-done-when-)
- [🤔 Troubleshooting](#-troubleshooting)
- [➡️ Next Module](#-next-module)

---

### 🎯 Our Goals for This Module
- Install the essential tools: Python, Git, and VS Code.
- Understand what a virtual environment is and how to use it.
- Run your first-ever Python script from your terminal.
- Learn the complete developer workflow: creating a branch, committing your work, pushing it to GitHub, and opening a Pull Request (PR).

---

### 🛠️ What You’ll Set Up
- **Python** (3.12 or newer) 🐍
- **Git** (for version control) 🔧
- **VS Code** (your code editor) 📝
- A **Virtual Environment** for this project (named `.venv`)

---

### ✅ Before You Start
- Make sure you have a GitHub account and have cloned this repository.
- **Windows users**: We recommend using PowerShell.
- **macOS/Linux users**: The built-in Terminal is perfect.

---

### Step 1: Install Python 3.12+
Python is the programming language we'll be using.

- **Download**: [python.org/downloads](https://www.python.org/downloads/)
- **Windows**: During installation, **make sure to check the box** that says “Add Python to PATH”. This is very important!
- **macOS (Homebrew)**: If you use Homebrew, you can run `brew install python@3.12`.

To check that it's installed correctly, open your terminal and run:
```bash
python --version
# If that doesn't work, try one of these:
# python3 --version
# py --version (Windows)
```
You should see `Python 3.12.x` or a newer version printed out.

---

### Step 2: Install Git 🔧
Git is a tool that helps us track changes in our code and collaborate with others.

- **Download**: [git-scm.com/downloads](https://git-scm.com/downloads)
- After installing, introduce yourself to Git. This name and email will be attached to all your future commits.
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global init.defaultBranch main
```

---

### Step 3: Install VS Code 📝
VS Code is a powerful, free code editor where you'll write all your code.

- **Download**: [code.visualstudio.com](https://code.visualstudio.com/)
- **Recommended Extensions**: After installing VS Code, open it and go to the Extensions view (Ctrl+Shift+X). Search for and install these to make your life easier:
  - `Python` (from Microsoft)
  - `Pylance`
  - `Black Formatter`
  - `Ruff`
- Finally, open this project folder in VS Code using **File → Open Folder**.

---

### Step 4: Create a Virtual Environment 📦

> **What's a Virtual Environment?** Think of it like a clean, separate toolbox for each project. It keeps all the specific tools (packages) for this project contained, so they don’t interfere with your other projects.

In your terminal, from the root folder of this project, create the environment:
```bash
python -m venv .venv
```
*(If that fails, try `python3 -m venv .venv` or `py -m venv .venv`)*

Now, **activate** it. You'll need to do this every time you work on the project.

- **Windows (PowerShell)**
  ```powershell
  .\.venv\Scripts\Activate.ps1
  ```
- **macOS/Linux (bash/zsh)**
  ```bash
  source .venv/bin/activate
  ```

You'll know it's working when you see `(.venv)` at the beginning of your terminal prompt!

Finally, let's upgrade `pip`, the tool we use to install Python packages:
```bash
python -m pip install -U pip
```

---

### Step 5: Write Your First Script ✨
Time to write your first line of Python code!

1.  In VS Code, create a new file in the root of the project called `hello.py`.
2.  Add the following code to the file:

    ```python
    print("Hello from Astral Family! 🚀")
    ```
3.  Save the file, and in your **activated** terminal, run it:
    ```bash
    python hello.py
    ```
    *(or `python3 hello.py`, `py hello.py`)*

You should see `Hello from Astral Family! 🚀` printed in your terminal. Congratulations!

---

### Step 6: The Git & GitHub Workflow 🔄
This is the core process every developer uses to contribute code. Let's walk through it.

1.  **Create a New Branch**: A branch is like a clean copy of the project where you can work without messing up the main version.
    ```bash
    git checkout -b module-0-onboarding
    ```

2.  **Add Your Files**: Tell Git which files you want to save. We'll add your new script and this `README.md` file.
    ```bash
    git add hello.py "module 0/README.md"
    ```

3.  **Commit Your Changes**: A commit is a "save point". You're saving a snapshot of your changes with a descriptive message.
    ```bash
    git commit -m "Module 0: setup tools and first script"
    ```

4.  **Push Your Branch**: Upload your branch and its commits from your computer to GitHub.
    ```bash
    git push -u origin module-0-onboarding
    ```

5.  **Open a Pull Request (PR)**:
    - Go to your repository on GitHub.
    - You’ll see a yellow banner with your branch name. Click the "Compare & pull request" button.
    - Give your PR a title, like `Module 0: Onboarding & Tools`.
    - Write a short description of what you did (e.g., "Set up my local environment and created the hello.py script.").
    - Click "Create pull request".

Awesome! You've just completed the core developer workflow. Now, a teammate can review your changes and merge them.

---

### Optional: Cloud Setups ☁️
If you want to skip local installation, you can explore these options later:
- **GitHub Codespaces**: A complete development environment that runs in your browser.
- **VS Code Dev Containers**: Uses Docker to run a pre-configured environment on your machine.
For now, learning the local setup is a valuable skill!

---

### 📝 Your Onboarding Checklist
- [ ] Install Python 3.12+ and verify the version.
- [ ] Install Git and configure your name/email.
- [ ] Install VS Code and the Python extension.
- [ ] Create and activate the `.venv` virtual environment.
- [ ] Upgrade `pip`.
- [ ] Create and successfully run `hello.py`.
- [ ] Create a new Git branch named `module-0-onboarding`.
- [ ] Commit and push your changes.
- [ ] Open your first Pull Request on GitHub!

---

### 🏁 Done When...
- Your Pull Request is approved and merged.
- You can confidently activate your virtual environment and run Python scripts.
- You understand the basic flow: branch → commit → push → PR.

---

### 🤔 Troubleshooting

<details>
  <summary><strong>Having trouble? Click here for common fixes.</strong></summary>

  - **"python: command not found"**
    - Try `python3` (on macOS/Linux) or `py` (on Windows).
    - If you're on Windows, you may have forgotten to check “Add Python to PATH” during installation. The easiest fix is to reinstall Python and make sure that box is checked.

  - **PowerShell says “running scripts is disabled”**
    - This is a security feature. You can allow scripts for your user only by running this command in PowerShell (not as an Administrator):
      ```powershell
      Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
      ```
    - Try activating the virtual environment again.

  - **`pip` installs packages to the wrong place**
    - Always use `python -m pip install ...` instead of just `pip install ...`. This ensures you're using the `pip` from your activated virtual environment.

  - **VS Code isn't using my virtual environment**
    - Open the command palette with `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac).
    - Type `Python: Select Interpreter`.
    - Choose the one that has `.venv` in its path.

  - **Git asks for my username/password on `git push`**
    - This is normal for the first time you connect to GitHub. Follow the prompts to sign in. It's often easier to set up an SSH key or a Personal Access Token (PAT) later on.
</details>

---

### ➡️ Next Module
Awesome work! You're all set up. Head over to **Module 1 — Python Basics I 🧱** to start learning about variables, numbers, strings, and more.

Happy coding! 🎉

[EN](../README.md) | 中文


<h1 align="center">Python 🐍 从零到面向对象编程 🚀</h1>
<p align="center">一条友好、实战的学习路径，帮助您从零开始学习 Python，并掌握扎实的面向对象编程（OOP）技能。为 Astral Family 组织量身打造。</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12+-blue.svg" alt="Python 版本">
  <img src="https://img.shields.io/badge/风格-边做边学-green.svg" alt="学习风格">
  <img src="https://img.shields.io/badge/重点-核心_&_OOP-purple.svg" alt="课程重点">
</p>

---

## 🧭 目录
- [✨ 你将学到什么](#-你将学到什么)
- [🎯 本课程有何不同](#-本课程有何不同)
- [👥 适合人群](#-适合人群)
- [✅ 先决条件](#-先决条件)
- [🛠️ 环境设置](#️-环境设置)
- [📚 课程大纲](#-课程大纲)
- [🔎 详细教学计划](#-详细教学计划)
- [🏗️ 实践项目](#️-实践项目)
- [🌱 后续步骤 (可选)](#-后续步骤-可选)
- [🔗 实用资源](#-实用资源)
- [🤝 如何贡献](#-如何贡献)
- [📄 许可证](#-许可证)

---

## ✨ 你将学到什么
课程结束后，您将能够：
- **编写清晰、可读的 Python 代码**，遵循专业标准。
- **掌握基本数据结构**，如列表、字典、集合和元组。
- 使用条件、循环和优雅的推导式来**控制程序流程**。
- 将代码**组织**成函数、模块和简单的包。
- 安全地**读写文件**（CSV/JSON 等常见格式）。
- **优雅地处理错误**，并添加日志来调试应用程序。
- 使用面向对象编程（OOP）原则**设计和构建自己的类**，以模拟现实世界概念。

本课程专注于 Python 核心和 OOP。我们**不**涉及 Web 框架、API 或数据库。

---

## 🎯 本课程有何不同
- **动手实践与项目驱动**: 通过实践学习。每个模块都包含实际练习，并逐步构建小型现实世界项目。
- **循序渐进**: 我们将复杂的主题分解为小而易于管理的步骤，确保您在不感到不知所措的情况下打下坚实的基础。
- **注重代码质量**: 从第一天起，您将学习编写不仅功能正常，而且整洁、文档良好、易于他人阅读的代码。
- **GitHub 工作流程**: 您将学习并使用标准开发工作流程：创建分支、提交代码和创建拉取请求（Pull Request），为实际协作做好准备。

---

## 👥 适合人群
- **完全的初学者**，无需任何编程经验。
- 了解一些 Python 基础知识，并希望通过结构化路径掌握 OOP 的**爱好者**。
- 使用 GitHub 指导 1-5 名学习者，并希望获得现成课程及明确检查点的**导师**。

**建议进度：** 6–10 周，兼职学习。

---

## ✅ 先决条件
- 一台能上网的电脑。
- 一个 GitHub 帐户。
- 了解基本的命令行操作会有所帮助，但不是必需的（我们会指导您完成所需的操作）。

---

## 🛠️ 环境设置
请遵循 **[模块 0：入门与工具](module%200/README.md)** 中的说明来设置完整的开发环境。基本要素包括：

1.  **安装 Python 3.12+**
    - Windows: 从 [python.org](https://www.python.org/downloads/) 安装（确保勾选 “Add Python to PATH”）。
    - macOS: `brew install python@3.12`
    - Linux: 使用系统的包管理器或 `pyenv`。

2.  **创建并激活虚拟环境**
    ```bash
    # 创建环境
    python -m venv .venv

    # 激活环境 (macOS/Linux 示例)
    source .venv/bin/activate

    # 升级 pip
    pip install -U pip
    ```

3.  **推荐工具**
    - **编辑器**: VS Code + 官方 Python 扩展。
    - **版本控制**: Git 和 GitHub 帐户。

---

## 📚 课程大纲
本课程分为 9 个核心模块，旨在带您从零开始，自信地构建面向对象的程序。

| 编号 | 模块 | 重点 |
|---|--------|-------|
| 0 | 入门与工具 ⚙️ | Shell, Git, Python 安装, venv, VS Code |
| 1 | Python 基础 I 🧱 | 语法, 变量, 数字, 字符串, 输入/输出 |
| 2 | 控制流 🔁 | if/elif/else, match, 循环, 推导式 |
| 3 | 数据结构 🧺 | str, list, tuple, set, dict, 切片, 可变性 |
| 4 | 函数与类型 🧩 | def, 参数, 返回值, 文档字符串, 类型提示 |
| 5 | 模块与包 🗂️ | 导入, 布局, 主入口, 简单项目设置 |
| 6 | 文件与数据 💾 | pathlib, with, CSV/JSON 读写, 简单错误处理 |
| 7 | 错误与日志 🧯 | 异常, 自定义错误, 日志基础 |
| 8 | OOP 与数据类 🏷️ | 类, 方法, 属性, dataclasses, 设计基础 |

完成核心模块后，您将在系列实践项目中应用所学技能。

---

## 🔎 详细教学计划

<details>
  <summary><strong>模块 0 — 入门与工具 ⚙️</strong></summary>

  - **学习**: 命令行基础，完整的 Git/GitHub 工作流程（克隆、分支、提交、推送、PR），Python 安装，虚拟环境，以及 VS Code 设置。
  - **构建**: 在本地运行此仓库，编写 "Hello, world!" 脚本，并提交您的第一个拉取请求。
</details>

<details>
  <summary><strong>模块 1 — Python 基础 I 🧱</strong></summary>

  - **学习**: 核心语法，变量，数据类型（`int`, `float`, `bool`, `str`），数学运算，f-string 格式化，以及用户输入/输出（`input()`, `print()`）。
  - **构建**: 一个微型计算器，一个单位转换器，以及一个字符串格式化脚本。
</details>

<details>
  <summary><strong>模块 2 — 控制流 🔁</strong></summary>

  - **学习**: 条件逻辑（`if`/`elif`/`else`），`match` 语句，循环（`for`/`while`），循环控制（`break`/`continue`），以及列表/字典/集合推导式。
  - **构建**: FizzBuzz 风格的程序，一个用于文本统计的脚本，以及一个使用 `match` 的简单规则引擎。
</details>

<details>
  <summary><strong>模块 3 — 数据结构 🧺</strong></summary>

  - **学习**: 深入学习字符串、列表、元组、集合和字典。涵盖切片、索引以及可变性与不可变性的关键概念。
  - **构建**: 一个单词计数器，一个字谜检查器，以及一个使用字典方法的简单电话簿。
</details>

<details>
  <summary><strong>模块 4 — 函数与类型 🧩</strong></summary>

  - **学习**: 定义函数（`def`），处理参数（`*args`, `**kwargs`），返回值，编写文档字符串（docstrings），以及使用类型提示来提高代码清晰度。
  - **构建**: 一个包含清晰文档和类型提示的小型实用工具库。
</details>

<details>
  <summary><strong>模块 5 — 模块与包 🗂️</strong></summary>

  - **学习**: 如何使用 `import`，将项目组织成多个文件，使用 `__name__ == "__main__"` 入口点，以及理解相对导入与绝对导入。
  - **构建**: 一个分割成多个文件、具有明确 `main.py` 起始点的小型项目。
</details>

<details>
  <summary><strong>模块 6 — 文件与数据 💾</strong></summary>

  - **学习**: 使用 `pathlib` 进行现代文件路径操作，上下文管理器（`with`），读写文本文件，以及处理 CSV 和 JSON 等结构化数据。
  - **构建**: 一个将数据从 CSV 文件转换为 JSON 文件并进行简单验证的命令行工具。
</details>

<details>
  <summary><strong>模块 7 — 错误与日志 🧯</strong></summary>

  - **学习**: 使用 `try`/`except`/`else`/`finally` 处理异常，引发自定义错误，以及使用 `logging` 模块记录应用程序事件。
  - **构建**: 重构之前的项目，加入健壮的错误处理和信息丰富的日志消息。
</details>

<details>
  <summary><strong>模块 8 — OOP 与数据类 🏷️</strong></summary>

  - **学习**: 面向对象编程的原理。涵盖类、`__init__`、方法、属性以及方便的 `@dataclass` 装饰器。
  - **构建**: 一个使用类和数据类来模拟现实世界领域（例如图书馆、银行或库存）的小型应用程序。
</details>

---

## 🏗️ 实践项目
完成核心模块后，选择 2-3 个项目来构建您的作品集。

1.  **任务跟踪器 CLI** 📝
    - **描述**: 一个命令行工具，用于添加、列出任务并将任务标记为完成。数据保存到 JSON 文件。
    - **概念**: 字典、列表、文件 I/O (JSON)、函数、简单错误处理。

2.  **费用分摊器** 💸
    - **描述**: 一个用于多人分摊餐厅账单（包括税和小费）的工具。结果可以导出为 CSV 文件。
    - **概念**: 函数、类型提示、字符串格式化、文件 I/O (CSV)。

3.  **抽认卡训练器** 🎴
    - **描述**: 一个基于终端的抽认卡应用程序，从 CSV 文件加载问题和答案，对用户进行测验，并跟踪得分。
    - **概念**: 循环、文件 I/O、模块化布局。

4.  **图书馆库存 (OOP)** 📚
    - **描述**: 一个管理图书馆库存的系统。使用类对 `Book`（书籍）、`Member`（会员）和 `Loan`（借阅）进行建模。实现借阅和归还规则。
    - **概念**: OOP、数据类、错误处理、日志记录。

---

## 🌱 后续步骤 (可选)
掌握 OOP 后，您可以探索以下中级主题：
- **测试**: 学习使用 `pytest` 编写代码测试的基础知识。🧪
- **代码风格**: 使用 `Black` 和 `Ruff` 自动强制执行一致的代码风格。🧼
- **打包**: 学习使用 `pyproject.toml` 打包您的项目。📦
- **GUI**: 使用像 `Tkinter` 这样的库创建简单的图形用户界面。🪟

---

## 🔗 实用资源
- [Python 官方教程](https://docs.python.org/zh-cn/3/tutorial/)
- [Python 官方文档](https://docs.python.org/zh-cn/3/)
- [用 Python 自动化繁琐的工作](https://automatetheboringstuff.com/) (英文)
- [Real Python](https://realpython.com/) (英文文章)
- [PEP 8 (代码风格指南)](https://peps.python.org/pep-0008/) (英文)

---

## 🤝 如何贡献
- 有想法或发现错误？请提交 issue。
- 遵循标准的 Git 工作流程：为每个模块或功能创建一个分支。
- 在提交拉取请求（Pull Request）之前，请务必测试您的代码并进行自我审查。
- 积极参与反馈以改进您的代码。

---

## 📄 许可证
本项目采用 MIT 许可证。详见 [LICENSE](https://github.com/Astral-Family/Python-Basics/blob/main/LICENSE) 文件。

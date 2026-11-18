# Day 01 – Python Basics

## How Code Reaches the Computer

Computers only understand machine code (binary). Every programming language is translated down to that level before it can produce output.

```
C       --> low-level (technical) language --> computer --> output
Python  --> high-level (easy) language --> low-level language --> computer --> output
```

- **C** is close to the machine, so it is fast but harder to read and write.
- **Python** is a high-level, easy-to-read language. The Python interpreter translates it into lower-level instructions that the computer runs.

## IDEs and Coding Environments

An **IDE** (Integrated Development Environment) is a tool for writing, running, and debugging code.

| Tool | Type | Notes |
|------|------|-------|
| **VS Code** | Desktop code editor | Lightweight, extensible; install the Python extension |
| **Jupyter Notebook** | Notebook (local) | Run code cell by cell; great for data science and learning |
| **Google Colab** | Notebook (cloud) | Jupyter in the browser; free, nothing to install, free GPU access |

## Python Rules to Remember

1. **Python is case-sensitive.** `name`, `Name`, and `NAME` are three different variables, and `True` is valid while `true` is an error.

## day-01: Data Types

| Type | Python name | Description | Examples |
|------|-------------|-------------|----------|
| Integer | `int` | Whole numbers | `0`, `1`, `2`, `-5` |
| Float | `float` | Numbers with a decimal point | `0.1`, `0.3`, `3.14` |
| String | `str` | Text inside single or double quotes | `'hello'`, `"Python"` |
| Multiline string | `str` | Text inside triple quotes; can span several lines | `"""line 1`<br>`line 2"""` |
| Boolean | `bool` | `True` or `False` (behave like `1` and `0`) | `True`, `False` |
| None | `NoneType` | Represents "no value" or an empty value | `None` |

## day-02: Variable, Operators
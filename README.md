# 🐍 Python by Purvi Jain

> A complete, structured Python learning course - from absolute basics to advanced concepts - built as interactive Jupyter Notebooks.

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Purvi_Jain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/purvi-jain-315683326)

---

## 📖 About This Repository

This repository is a **self-contained Python course** organised into 10 numbered folders — one per topic. Every folder contains a Jupyter Notebook (`.ipynb`) with:

- 📝 **Markdown cells** explaining the concept, theory, and rules
- 📊 **Comparison tables** for quick reference
- ✅ **Runnable code cells** with real examples
- 💡 **Tips, common mistakes, and best practices**
- 🔗 **Cross-references** to related topics

The course is designed for **beginners who want to reach an intermediate/advanced level** while building real mini-projects along the way.

---

## 📂 Repository Structure

<p align="center">
<img width="500" height="400" alt="Image" src="https://github.com/user-attachments/assets/183aa068-3384-4d8e-be48-9e03248b4334" />
</p>

```
Python-by-Purvi-Jain/
│
├── 01_Python_Basics/
├── 02_Control_Flow/
├── 03_Data_Structures/
├── 04_Functions/
├── 05_Modules/
├── 06_File_Handling/
├── 07_Exception_Handling/
├── 08_Classes_and_Objects/
├── 09_Advanced_Python/
└── 10_Project/
```

---

## 📚 Syllabus

### 1 - Python Basics
> *Foundation of everything. Start here.*

| Topic | What you'll learn |
|-------|-------------------|
| Variables & Data Types | `int`, `float`, `str`, `bool`, `NoneType`, `type()` |
| Type Casting | `int()`, `float()`, `str()`, `bool()`, truthy/falsy, ValueError |
| Input & Output | `print()` with `sep`/`end`, `input()`, casting user input |
| Operators | Arithmetic, comparison, logical, assignment, identity, membership |
| String Methods | `.upper()`, `.split()`, `.join()`, `.replace()`, slicing, indexing |
| f-strings & Formatting | `f"{val:.2f}"`, alignment, zero-padding, `f"{x=}"` debug trick |
| Comments & Style | PEP 8, docstrings, `__doc__`, inline comments |

---

### 2 - Control Flow
> *Control which code runs, when, and how many times.*

| Topic | What you'll learn |
|-------|-------------------|
| if / elif / else | Conditions, truthy checks, ternary operator, chained comparisons |
| Nested Conditions | Guard clause pattern, flattening deep nesting |
| for Loops | Iterating lists/strings/dicts, `enumerate()`, `zip()`, nested loops |
| while Loops | Unknown iterations, flags, `while-else` |
| break / continue / pass | Loop control, search patterns, `for-else` |
| range() Usage | All three signatures, negative step, indexing, membership |
| List Comprehensions | Filter, transform, nested, set/dict/generator expressions |

---

### 3 - Data Structures
> *Choosing the right structure is half the solution.*

| Topic | What you'll learn |
|-------|-------------------|
| Lists & Indexing | Positive/negative indexing, 11 key methods, sorting |
| Tuples | Immutability, single-item syntax, unpacking, dict keys |
| Sets | Deduplication, fast membership, set math (`\|`, `&`, `-`, `^`) |
| Dictionaries | `.get()`, `.items()`, word-count pattern, `setdefault()` |
| Nested Structures | List of dicts, dict of dicts, 2D matrix, `json.dumps` |
| Dict / Set Comprehensions | Invert dict, filter, transform, Celsius→Fahrenheit |
| Slicing & Unpacking | `[start:stop:step]`, slice assignment, `*rest`, `*mid` |

---

### 4 - Functions
> *Write once, reuse everywhere. The heart of clean code.*

| Topic | What you'll learn |
|-------|-------------------|
| Defining Functions | `def`, anatomy, first-class objects, `__doc__`, `help()` |
| Parameters & Defaults | Positional, keyword, defaults, mutable default bug + fix |
| `*args` & `**kwargs` | Variable positional/keyword args, parameter order rule, unpacking |
| Return Values | Multiple returns (tuple), early return, guard clauses |
| Scope & Closures | LEGB rule, `global`, `nonlocal`, factory functions |
| Lambda Functions | Anonymous functions, best use as `key=`, dispatch tables |
| map / filter / reduce | Higher-order functions vs list comprehensions, `functools` |

---

### 5 - Modules
> *Organise, share, and reuse your code across files.*

| Topic | What you'll learn |
|-------|-------------------|
| import & from import | `import`, `from x import y`, aliases with `as` |
| Standard Library | `os`, `sys`, `pathlib`, `shutil` |
| math & random | `math.sqrt`, `math.pi`, `random.choice`, `random.seed` |
| datetime | `date`, `datetime`, `timedelta`, formatting with `strftime` |
| Creating Custom Modules | Writing `.py` modules, `__all__`, package `__init__.py` |
| pip & Virtual Environments | `pip install`, `requirements.txt`, `venv` |
| `__name__ == "__main__"` | Script vs import mode, entry point pattern |

---

### 6 - File Handling
> *Read from and write to the real world.*

| Topic | What you'll learn |
|-------|-------------------|
| open(), read, write | File objects, `read()`, `readline()`, `readlines()`, `write()` |
| with Statement | Context manager for files, automatic close |
| File Modes | `r`, `w`, `a`, `b`, `r+`, mode combinations |
| CSV Handling | `csv.reader`, `csv.DictReader`, `csv.writer`, `csv.DictWriter` |
| JSON Read & Write | `json.load()`, `json.dump()`, `json.loads()`, `json.dumps()` |
| os.path Utilities | `os.path.exists()`, `join()`, `basename()`, `splitext()` |
| Directory Operations | `os.makedirs()`, `os.listdir()`, `shutil.copy()`, `glob` |

---

### 7 - Exception Handling
> *Write code that fails gracefully.*

| Topic | What you'll learn |
|-------|-------------------|
| try / except / else | Specific exceptions, `as e`, multiple clauses, `else` block |
| finally Block | Guaranteed cleanup, resource management, DB patterns |
| Common Exceptions | 15 daily exceptions — what triggers each, how to handle |
| raise & Custom Errors | `raise`, re-raise, chaining with `from`, custom exception classes |
| Exception Hierarchy | `BaseException` tree, parent catches children, ordering rules |
| Logging Basics | 5 log levels, `basicConfig`, named loggers, `exc_info=True`, file handlers |

---

### 8 - Class And Objects
> *Model the real world with OOP.*

| Topic | What you'll learn |
|-------|-------------------|
| Classes & `__init__` | Blueprint → instance, `self`, anatomy, `Counter` with defaults |
| Instance vs Class Variables | Shared vs per-object, shadowing trap, `__dict__` inspection |
| Methods & self | Instance / `@classmethod` / `@staticmethod`, method chaining |
| Inheritance | `super()`, single/multi-level/multiple, `isinstance`, MRO |
| Polymorphism | Method overriding, duck typing, generic functions |
| Dunder Methods | `__repr__`, `__str__`, `__add__`, `__len__`, `__call__`, context managers |
| @property & Decorators | Getter/setter/deleter, read-only, name mangling, lazy caching |

---

### 9 - Advance Python Concepts
> *What separates a beginner from a developer.*

| Topic | What you'll learn |
|-------|-------------------|
| Iterators & Generators | `__iter__`/`__next__`, `yield`, `yield from`, memory comparison, pipelines |
| Decorators (Advanced) | Timer, retry, memoize, `functools.wraps`, decorator factories, stacking |
| Context Managers | Class-based, `@contextmanager`, transaction manager, `contextlib.suppress` |
| Threading & Multiprocessing | GIL, `Lock`, `ThreadPoolExecutor`, `ProcessPoolExecutor`, `as_completed` |
| async / await | Coroutines, event loop, `asyncio.gather`, tasks, async context managers |
| Regular Expressions | `re` module, groups, named groups, `sub`, validation, `re.compile` |
| Type Hints & Dataclasses | `Optional`, `Union`, `@dataclass`, `frozen`, `field()`, `__post_init__` |

---

### 10 - Projects
> *Apply everything you've learned in real mini-projects.*

| # | Project | Concepts Applied |
|---|---------|-----------------|
| 1 | 🔢 **Calculator** | Functions, dispatch dict, OOP, `deque`, exception handling |
| 2 | ⏱️ **Timer & Stopwatch** | OOP, `@property`, `@dataclass`, `time.perf_counter`, lap tracking |
| 3 | 🐍 **Snake Water Gun Game** | Enum, OOP, `random`, statistics, streak detection, `Counter` |
| 4 | 📒 **Contact Book** | JSON I/O, regex validation, CRUD, `@dataclass`, search & filter |
| 5 | 🎯 **Number Guessing Game** | Difficulty enum, binary search, scoring, history, statistics |

---

## 🚀 Getting Started

### Prerequisites

- Python **3.10+** (3.11 recommended)
- Jupyter Notebook or JupyterLab
- VS Code with the Jupyter extension (optional but recommended)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Purvijain1234/Python-by-Purvi-Jain.git
cd Python-by-Purvi-Jain

# 2. Create a virtual environment
python -m venv .venv

# Activate — Windows
.venv\Scripts\activate

# Activate — macOS / Linux
source .venv/bin/activate

# 3. Install dependencies
pip install jupyter notebook ipykernel

# 4. Launch Jupyter
jupyter notebook
```

### Open in VS Code

```bash
# Install the Jupyter extension, then:
code .
# Click any .ipynb file → runs in VS Code's built-in notebook editor
```

---

## 🎮 Projects Deep Dive

### 🔢 Project 1 - Calculator

A fully featured command-line calculator with memory and history.

**Features:**
- Supports `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Memory operations: M+ (store), MR (recall), MC (clear)
- History of last 5 calculations using `collections.deque`
- Expression parser: type `10 + 5` as a string
- Graceful error handling for division by zero and invalid input

```python
calc = Calculator()
calc.parse_and_compute("2 ** 10")   # 1024
calc.memory_add(calc.last)
calc.show_history()
```

---

### ⏱️ Project 2 - Timer & Stopwatch

Two precision timing tools built with `time.perf_counter`.

**Stopwatch features:**
- Start, stop, pause, resume
- Lap recording with `LapRecord` dataclass
- Fastest / slowest / average lap analysis
- Time formatted as `MM:SS.ms`

**Countdown Timer features:**
- Set any duration in seconds
- Live progress bar using `█` blocks
- Alert on completion

```python
sw = Stopwatch()
sw.start()
time.sleep(1.5)
sw.lap()
sw.stop()
sw.summary()
```

---

### 🐍 Project 3 - Snake Water Gun Game

The classic Indian hand game with full statistics tracking.

**Rules:**
```
🐍 Snake  drinks  💧 Water  → Snake wins
💧 Water  drowns  🔫 Gun    → Water wins
🔫 Gun    kills   🐍 Snake  → Gun wins
```

**Features:**
- `Choice` Enum + `BEATS` dict for clean win logic
- Win/loss/streak tracking with 🔥 indicator
- Random win/lose/tie messages
- Favourite move analysis using `Counter`
- Full final stats: win rate, best streak, overall verdict

```python
game = GameSession("Purvi")
result = game.play_round(Choice.SNAKE)
game.final_stats()
```

---

### 📒 Project 4 - Contact Book

A persistent CRUD contact manager saved to JSON.

**Features:**
- `Contact` dataclass with automatic validation
  - Indian mobile regex: `^[6-9]\d{9}$`
  - Email format validation
  - Auto `.title()` casing
- JSON save/load for persistence across sessions
- Full CRUD: add, get, update, delete
- Search across name, phone, email, and tags
- Filter by tag, sort by name or phone

```python
book = ContactBook("contacts.json")
book.add(Contact("Purvi", "Jain", "9876543210", "purvi@ex.com", ["friend"]))
book.search("friend")
book.save()
```

---

### 🎯 Project 5 - Number Guessing Game

A multi-difficulty guessing game with scoring and statistics.

**Difficulty levels:**

| Level | Range | Max Guesses |
|-------|-------|-------------|
| Easy | 1–50 | 10 |
| Medium | 1–100 | 7 |
| Hard | 1–200 | 6 |

**Features:**
- Hot/cold hints (Easy) and Higher/Lower (Medium/Hard)
- Scoring: `1000 − (100 × extra_guesses) + time_bonus`
- Binary search auto-play for demo
- Multi-game history with average guesses and high score

```python
game = GuessingGame(Difficulty.MEDIUM, "Purvi")
game.play_one()
game.overall_stats()
```

---

## 📋 Topics Covered - Full Checklist

```
✅  1-Python Basics          ✅  6-File Handling
✅  2-Control Flow           ✅  7-Exception Handling
✅  3-Data Structures        ✅  8-Class And Objects
✅  4-Functions              ✅  9-Advance Python Concepts
✅  5-Modules                ✅  10-Projects
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.11 | Core language |
| Jupyter Notebook | Interactive execution |
| VS Code + Jupyter Extension | Recommended editor |
| `json`, `csv`, `re`, `os` | Standard library modules |
| `dataclasses`, `enum`, `typing` | Modern Python features |
| `asyncio`, `threading`, `multiprocessing` | Concurrency |
| `logging`, `functools`, `collections` | Utilities |

---

## 🤝 Contributing

Contributions are welcome! If you find a bug, have a suggestion, or want to add a topic:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/add-numpy-notebook`
3. Commit your changes: `git commit -m "Add NumPy basics notebook"`
4. Push to the branch: `git push origin feature/add-numpy-notebook`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author

**Purvi Jain**

[![GitHub](https://img.shields.io/badge/GitHub-Purvijain1234-181717?style=flat-square&logo=github)](https://github.com/Purvijain1234)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Purvi_Jain-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/purvi-jain-315683326)

---

<div align="center">

⭐ **If this course helped you, please give it a star!** ⭐

*Made with ❤️ and lots of Python*

</div>

# 🛡️ 7 - Exception Handling

An **exception** is an event that disrupts the normal flow of a program. Instead of letting your program crash, Python lets you **catch** exceptions, handle them gracefully, and keep running.

> 🔑 The Python philosophy: **"It's easier to ask forgiveness than permission"** (EAFP) - try the operation, catch the error if it fails, rather than checking every precondition upfront.

**Topics covered:**
1. `try` / `except` / `else`
2. `finally` Block
3. Common Built-in Exceptions
4. `raise` & Custom Exceptions
5. Exception Hierarchy
6. Logging Basics

---
## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| `try/except/else` | Catch specific exceptions; `else` runs only on success; catch specific before broad |
| `finally` | Always runs - use for cleanup (close files, connections, locks) |
| Common exceptions | Know the ~15 daily exceptions and what triggers each |
| `raise` | Raise with a clear message; re-raise with bare `raise`; chain with `raise X from Y` |
| Custom exceptions | Inherit from `Exception`; add attributes for extra context |
| Exception hierarchy | Parent catches children; never catch `BaseException`; specific before broad |
| Logging | Use `logging` over `print` in production; name your loggers; use `exc_info=True` for tracebacks |

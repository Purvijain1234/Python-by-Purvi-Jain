# 📦 5 - Modules
This notebook covers everything you need to know about Python's module system - from importing built-in libraries to building and distributing your own.

**Topics covered:**
1. `import` & `from import`
2. Standard Library (`os`, `sys`)
3. `math` & `random`
4. `datetime`
5. Creating Custom Modules
6. `pip` & Virtual Environments
7. `__name__ == "__main__"`

---
## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| `import` & `from import` | Prefer explicit imports; use `as` for long module names; avoid `import *` |
| `os` & `sys` | `os` = filesystem & environment; `sys` = interpreter version, args, path |
| `math` & `random` | `math` is deterministic; `random` needs `seed()` for reproducibility; use `secrets` for security |
| `datetime` | `strftime` → string; `strptime` → datetime; arithmetic via `timedelta` |
| Custom modules | Any `.py` file is a module; use `__all__` to define public API; packages need `__init__.py` |
| `pip` & venv | Install with `pip install`; always use a virtual environment per project |
| `__name__` | `== "__main__"` only when run directly — use it to guard script-only code |


# 🚀 9 - Advance Python Concepts

This notebook covers the features that separate a **Python beginner from a Python developer**. These concepts appear in real codebases, open-source libraries, and technical interviews.

> 🔑 Master these and you can read and write professional-grade Python.

**Topics covered:**
1. Iterators & Generators
2. Decorators (Advanced)
3. Context Managers
4. Threading & Multiprocessing
5. `async` / `await`
6. Regular Expressions
7. Type Hints & Dataclasses
---
## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| Iterators & Generators | `__iter__`/`__next__` protocol; `yield` pauses and resumes; generators are lazy and memory-efficient |
| Decorators | Wrap functions with `@functools.wraps`; factory decorators take arguments; stack multiple with `@a @b` |
| Context Managers | `with` guarantees cleanup; class-based (`__enter__`/`__exit__`) or `@contextmanager` with `yield` |
| Threading | I/O-bound concurrency; `Lock` for thread safety; `ThreadPoolExecutor` for pools |
| Multiprocessing | CPU-bound parallelism; bypasses GIL; `ProcessPoolExecutor` for pools |
| async/await | Single-thread cooperative concurrency; `asyncio.gather` for parallel coroutines |
| Regex | `re.search/findall/sub/compile`; groups for extraction; pre-compile with `re.compile` |
| Type hints | Annotations don't enforce at runtime; use `Optional`, `Union`, `List`, `Dict`, `Callable` |
| Dataclasses | `@dataclass` auto-generates `__init__/repr/eq`; `frozen=True` for immutability; `field()` for defaults |


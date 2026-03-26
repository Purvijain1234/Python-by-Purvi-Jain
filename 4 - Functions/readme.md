# ⚙️ 4 - Functions
A **function** is a reusable block of code that performs a specific task. Functions are the primary tool for avoiding repetition (**DRY - Don't Repeat Yourself**) and breaking a large problem into smaller, manageable pieces.

**Topics covered:**
1. Defining Functions
2. Parameters & Defaults
3. `*args` & `**kwargs`
4. Return Values
5. Scope & Closures
6. Lambda Functions
7. `map` / `filter` / `reduce`

---
## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| Defining functions | `def name(params): → return value`; functions are first-class objects |
| Parameters & defaults | Defaults must come last; **never** use a mutable object as a default - use `None` |
| `*args` / `**kwargs` | `*args` → tuple of extra positionals; `**kwargs` → dict of extra keywords |
| Return values | `return a, b` returns a tuple; bare `return` or no `return` → `None` |
| Scope (LEGB) | L → E → G → B lookup order; use `global` / `nonlocal` sparingly |
| Closures | Inner functions that capture their enclosing scope - basis for factories & decorators |
| Lambda | Anonymous one-liner; best as `key=` argument - use `def` when naming is needed |
| map / filter / reduce | Higher-order functions; list comprehensions are often more readable for simple cases |

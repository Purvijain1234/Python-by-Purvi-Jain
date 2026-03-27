# 🏗️ 8 - Class And Objects

**Object-Oriented Programming (OOP)** is a paradigm that models real-world entities as **objects** - bundles of **data (attributes)** and **behaviour (methods)**. A **class** is the blueprint; an **object** is a concrete instance built from that blueprint.

> 🔑 The four pillars of OOP: **Encapsulation**, **Abstraction**, **Inheritance**, **Polymorphism**.

**Topics covered:**
1. Classes & `__init__`
2. Instance vs Class Variables
3. Methods & `self`
4. Inheritance
5. Polymorphism
6. Dunder (Magic) Methods
7. `@property` & Decorators

---
## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| Classes & `__init__` | Blueprint → instance; `self` always refers to the current object |
| Instance vs class vars | Instance vars are per-object; class vars are shared - beware the shadowing trap |
| Methods & `self` | Instance → `self`; Class → `@classmethod`/`cls`; Utility → `@staticmethod` |
| Inheritance | `super().__init__()` to chain constructors; specific → general in `except` and MRO |
| Polymorphism | Same method name, different behaviour; duck typing - if it has the method, use it |
| Dunder methods | Make objects behave like built-ins; `__repr__` for devs, `__str__` for users |
| `@property` | Getter/setter without breaking API; `_name` protected, `__name` name-mangled |

### Four pillars of OOPs
```
Encapsulation  → bundle data + methods; use _ and __ for access control
Abstraction    → hide implementation details (properties, NotImplementedError)
Inheritance    → reuse & extend - class Child(Parent)
Polymorphism   → same interface, different behaviour - overriding & duck typing
```

# 🗂️ 3 - Data Structures
Data structures are how Python **organises and stores collections of data**. Choosing the right one has a huge impact on code clarity and performance.

**Topics covered:**
1. Lists & Indexing
2. Tuples
3. Sets
4. Dictionaries
5. Nested Structures
6. List Comprehensions
7. Dict / Set Comprehensions
8. Slicing & Unpacking

---
### Quick comparison
| Structure | Ordered | Mutable | Duplicates | Syntax |
|-----------|---------|---------|------------|--------|
| List | ✅ | ✅ | ✅ | `[1, 2, 3]` |
| Tuple | ✅ | ❌ | ✅ | `(1, 2, 3)` |
| Set | ❌ | ✅ | ❌ | `{1, 2, 3}` |
| Dict | ✅ (3.7+) | ✅ | Keys: ❌ | `{"a": 1}` |

---

## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| Lists | Ordered, mutable; `append/insert/remove/pop/sort` are your daily tools |
| Tuples | Ordered, immutable; use for fixed data, multiple return values, and dict keys |
| Sets | Unordered, unique items; blazing-fast `in` checks; great for deduplication and set math |
| Dicts | Key-value pairs; use `.get(key, default)` to avoid KeyError; iterate with `.items()` |
| Nested structures | List of dicts for records; dict of lists for grouping; use `json.dumps` to inspect |
| List comprehensions | `[expr for x in it if cond]` - concise but keep them readable |
| Dict/Set comprehensions | `{k: v for ...}` and `{expr for ...}` - concise and readable |
| Slicing & unpacking | `seq[start:stop:step]`; starred `*rest` captures remaining items |

### Choosing the right structure
```
Need order + can change?       → List
Need order + must NOT change?  → Tuple
Need uniqueness + fast lookup? → Set
Need key-value mapping?        → Dict
```



# 🗂️ 6 - File Handling
This notebook covers everything you need to read, write, and manage files in Python - from basic text I/O to working with CSV, JSON, and the filesystem.

**Topics covered:**
1. `open()`, read, write
2. `with` statement
3. File modes (`r`, `w`, `a`, `b`)
4. CSV handling
5. JSON read & write
6. `os.path` utilities
7. Directory operations

---
## ✅ Summary

| Topic | Key Takeaway |
|-------|--------------|
| `open()`, read, write | Use `.read()`, `.readline()`, `.readlines()`, or iterate directly; always call `.close()` |
| `with` statement | **Always** use `with open(...) as f` — it auto-closes on exit, even after exceptions |
| File modes | `'r'` read · `'w'` write (wipes!) · `'a'` append · `'x'` exclusive · `'b'` binary |
| CSV | Use `csv.DictReader` / `csv.DictWriter` for column-name access; always pass `newline=''` |
| JSON | `dump`/`load` for files · `dumps`/`loads` for strings; use `indent=4` for human-readable output |
| `os.path` | Use `join()` for paths, `exists()` / `isfile()` before I/O, `splitext()` to split name+ext |
| Directory ops | `os.makedirs(exist_ok=True)` to create · `os.walk()` to traverse · `shutil.rmtree()` to delete |

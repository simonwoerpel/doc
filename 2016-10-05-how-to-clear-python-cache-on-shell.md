---
title:  "How To Clear Python Cache"
categories: doc-notes
---

Sometimes it can get confusing while debbuging apparently "correct" python code if there are some old `*.pyc`-files in the working directory.

They are (for mysterious reasons) sometimes still imported as modules by the python interpreter, even if the corresponding `*.py`-file was deleted already.

This one-liner keeps it clean:

```bash
find . -name "*.pyc" | xargs rm
```

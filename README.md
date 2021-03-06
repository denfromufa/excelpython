# ExcelPython v2

Write Excel user-defined functions and macros in Python!

```python
from xlpython import *

@xlfunc
@xlarg("x", "nparray", 2)
@xlarg("y", "nparray", 2)
def matrixmult(x, y):
    return x.dot(y)
```

![image](https://cloud.githubusercontent.com/assets/5197585/3907706/6c3a2cea-22fd-11e4-812f-41c814d1cc54.png)

Check out the [tutorials](docs/) to get started! The only prerequisites are Excel and Python (2.6 - 3.x) with PyWin32 installed.

### About ExcelPython

ExcelPython is a lightweight, easily distributable library for interfacing Excel and Python. It enables easy access to Python scripts from Excel VBA, allowing you to substitute VBA with Python for complex automation tasks which would be facilitated by Python's extensive standard library while sparing you the complexities of Python COM programming.

### Help me!

Check out the [docs](docs/) folder for tutorials to help you get started and links to other resources. Failing that, try the [issues section](https://github.com/ericremoreynolds/excelpython/issues?q=) or the [discussion forum on SourceForge](https://sourceforge.net/p/excelpython/discussion/general/).

If you still don't find your answer, need more help, find a bug, think of a useful new feature, or just want to give some feedback by letting us know what you're doing with ExcelPython, please go ahead and create an [issue ticket](https://github.com/ericremoreynolds/excelpython/issues/new)!

# Baum

This package can be pip installed and run from the command line like this:

```
baum
```

output:

```
├── src/
│   ├── baum/
│   │   ├── __pycache__/
│   │   │   ├── __init__.cpython-313.pyc
│   │   │   └── tree.cpython-313.pyc
│   │   ├── __init__.py
│   │   └── tree.py
│   └── baum.egg-info/
│       ├── PKG-INFO
│       ├── SOURCES.txt
│       ├── dependency_links.txt
│       └── top_level.txt
├── .gitignore
├── LICENSE.txt
├── README.md
├── localtest.py
└── pyproject.toml
```
## Install

```
pip install -i https://test.pypi.org/simple/ baum-CodersBringChange
```

From [TestPyPI](https://test.pypi.org/project/baum-CodersBringChange)

## Features

- Shows ASCII tree of current folder and beyond.
- Sorts by type (folders on top), then by name.
- Can be run from terminal or imported in Python code.

## Import in exising code

```
from baum import tree

tree.main()
```

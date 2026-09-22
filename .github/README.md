[![PyPI version](https://img.shields.io/pypi/v/alibrex.svg)](https://pypi.org/project/alibrex/)
[![Python versions](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11%20%7C%203.12%20%7C%203.13-blue.svg)](https://pypi.org/project/alibrex/)
[![Downloads](https://static.pepy.tech/badge/alibrex)](https://pepy.tech/project/alibrex)

# alibrex

- `alibrex` is a Python package that lets you drive Alibre Design from ordinary Python, wrapping the AlibreX automation interface so it behaves like a normal module.
  - What it does
    - Exposes the whole AlibreX API from one namespace, including `CurrentPart()`, `CurrentAssembly()`, and `connect()`.
    - Ships type information for each interface and enum, so autocomplete and hover documentation work in your editor.
    - Works with editors and type checkers that understand standard Python type stubs.
    - Comes with notebooks, examples, and demo scripts to learn from.
  - What you need
    - Alibre Design version 29 or later, installed and running.
    - Python 3.9 or newer on Windows.
  - Getting started
    - Install it with `pip install alibrex`.
    - Open a part in Alibre Design.
    - Run `from alibrex import CurrentPart` and then `CurrentPart()` to get hold of that part.
    - Browse `source/examples/` and `source/notebooks/` for worked examples.
  - Where things live
    - `source/` holds the examples, notebooks, demos, and helper scripts.
    - `documentation/` holds reference notes.
  - Good to know
    - Your code changes the live model straight away, so save your work before experimenting.
  - Use it under the MIT License.

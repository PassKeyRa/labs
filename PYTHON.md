# Python apps development best practices

* Create a code repository and implement version control

* Use virtual environments to keep the system in order

* Create readable and structured documentation

* Write unit-tests to do not waste time on huge bug fixes later

* Use linters to keep the code readable and prevent bugs

* Create `requirements.txt` file with used Python packages list

## Flask framework

### Pros

I chosed Flask framework because:

* It is very easy to understand

* It was fast to develop a small web application using Flask

* It's quite customizable

### Cons

* More security risks, because of customization

* More complex tech stack

* More complicated maintenance for complex systems

## Linters

The most popular Python linters are:

* Pylint

* Flake8

* PyFlakes

I used Pylint for Python that showed me four mistakes:

```
timeweb.py:1:0: C0114: Missing module docstring (missing-module-docstring)
timeweb.py:12:0: C0116: Missing function or method docstring (missing-function-docstring)
timeweb.py:3:0: C0411: standard import "from datetime import datetime" should be placed before "import pytz" (wrong-import-order)
timeweb.py:1:0: W0611: Unused import time (unused-import)
```

Also, I used markdownlint linter for Markdown docs.
It printed me the following:

```
PYTHON.md:15: MD012 Multiple consecutive blank lines
PYTHON.md:5: MD013 Line length
PYTHON.md:51: MD013 Line length
```

All mistakes were fixed as it was possible

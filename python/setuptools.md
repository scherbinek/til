# How to use setuptools for self-referencing

A nice way to reference several classes and its methods from different subfolder is by installing the project as self-reference.

According to its python runtime the classes from the project are registered as module.

A file `setup.py` with the following content in the project root

```python
from setuptools import setup, find_packages

setup(name='project-folder-name', version='0.1', packages=find_packages())
```

Afterward you can install every classes and its methods by the following command

```shell
(env) pip install -e .
```

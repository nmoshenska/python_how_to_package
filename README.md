# How to package a Python project

PyPI is the Python package index. Repositories in PyPI can be installed using `pip`, the Python package manager. To post code to the PyPI repository, take the following steps:

## Create a LICENSE
## Create a README
Make sure it's descriptive, and includes instructions for possible installation. Contributors will appreciate having this easy, accessible introduction to your project, goals, and possible future directions. 

Here's a [great checklist](https://github.com/ddbeck/readme-checklist/blob/main/checklist.md) for READMEs! 
## Create a build script (setup.py)

setup.py is the build script for setuptools. It tells setuptools about your package (such as the name and version) as well as which code files to include. Your setup.py file is what describes your package, and tells setuptools how to package, build and install it.


**Written for CSC630 in fall 2020 by Sarah, Gaia, Nikol, and Ali**

**Adapated from [python.org](https://packaging.python.org/tutorials/packaging-projects/)**

# Python Project Development Guide

## Requirements Files
- **requirements.txt**: Specifies dependencies required to run the production code of the Python project.
- **requirements_dev.txt**: Specifies dependencies required for development and testing purposes, separate from production dependencies.

## tox.ini
- Used for testing the Python package against different versions of Python.
- **How Tox Works**:
  1. Creates virtual environments.
  2. Installs dependencies and packages.
  3. Runs specified commands.
  - It's a combination of `virtualenvwrapper` and `makefile`.
  - Creates a `.tox` directory.

## pyproject.toml
- Alternative to `setup.cfg` for configuring Python projects.
- Contains project configuration such as build tools, package name, version, author, license, and dependencies.

## setup.cfg
- Used by setuptools to configure packaging and installation of a Python project.

## Testing Python Applications
### Types of Testing
- **Automated Testing**
- **Manual Testing**

### Modes of Testing
- **Unit Testing**
- **Integration Testing**

### Testing Frameworks
- pytest
- unittest
- robotframework
- selenium
- behave
- doctest

### Code Style and Syntax Checking
- **Pylint**
- **flake8** (combines pylint, pycodestyle, and mccabe)
- pycodestyle


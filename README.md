# Python.Tox


[![Build and Test](https://github.com/build-and-test/Python.Tox/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/build-and-test/Python.Tox/actions/workflows/build-and-test.yml?query=branch%3Amain)

Uses Tox to create and manage isolated Python virtual environments.

# Advantages

- Well-known Python tools and workflow
- Works on Windows, Mac, and Linux
- Fast

# Limitations

- Assumes Python is available on your PATH
- Assumes Python is called `python3` on Mac/Linux
- Uses system-installed shared Python, which could be any version and could already have some packages installed
- Installs Tox in the system Python

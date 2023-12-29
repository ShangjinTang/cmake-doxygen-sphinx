# README

## Introduction

This is a demo application which shows how to automatically generate
documentation using Doxygen, Breathe and Sphinx.

This README file should be included in the docs as the main page.

## Prerequisites

### System Requirements

- [Doxygen](https://github.com/doxygen/doxygen)

```bash
sudo apt install doxygen
```

### Python Packages

- [Sphinx](https://github.com/sphinx-doc/sphinx) & [Sphinx ReadTheDocs Theme](https://github.com/readthedocs/sphinx_rtd_theme)
- [Breathe](https://github.com/breathe-doc/breathe)
- [m2r2](https://github.com/CrossNox/m2r2)

```bash
pip install sphinx sphinx_rtd_theme breathe m2r2
```

## Building

To build the project, first cd to its directory, and then run:

```bash
cmake -S . -B build
cmake --build build
```

The documents with be generated in `build/doc`.

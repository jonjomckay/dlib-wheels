# Dlib binary distribution

[![Build](https://github.com/alesanfra/dlib-wheels/actions/workflows/build.yaml/badge.svg)](https://github.com/alesanfra/dlib-wheels/actions/workflows/build.yaml)
[![PyPI version](https://badge.fury.io/py/dlib-bin.svg)](https://badge.fury.io/py/dlib-bin)


This project creates a pre-compiled distrubution of [dlib](https://github.com/davisking/dlib) ready to be used in your python projects.

With `dlib-bin` you're just one `pip install` away from your next machine learning project!

Currently building 64 bits wheels for:
- Windows
- MacOS universal2 (Intel and Apple Silicon)
- Linux:
  - [manylinux2010](https://www.python.org/dev/peps/pep-0571) for glibc-based distributions (e.g. Ubuntu)
  - [musllinux](https://www.python.org/dev/peps/pep-0656) for musl-based distributions (e.g. Alpine)

## How to install this distribution?

Just open a terminal and type:

```bash
pip install dlib-bin
```

## How to contribute?

In order to trigger a new deploy, update the `BUILD_COMMIT` variable in `.github/workflows/build.yaml` file with the new tag/commit pushed on the [dlib](https://github.com/davisking/dlib) repository. 

# protoactor-python
Proto Actor - Ultra fast distributed actors

[![Join the chat at https://gitter.im/AsynkronIT/protoactor](https://badges.gitter.im/AsynkronIT/protoactor.svg)](https://gitter.im/AsynkronIT/protoactor?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/AsynkronIT/protoactor-python.svg?branch=master)](https://travis-ci.org/AsynkronIT/protoactor-python)

# Getting Started

Ensure you have Python 3.6 with pip installed.

```
$ pip3 install virtualenv
$ virtualenv dev.venv
$ source dev.venv/bin/activate # on POSIX systems
$ .\dev.venv\Scripts\activate.ps1 # on Windows
$ pip3 install -r requirements.dev.txt
```
## Run mypy

```
mypy --python-version 3.6 --fast-parser -p protoactor
```

## Run tests

```
$ tox
```

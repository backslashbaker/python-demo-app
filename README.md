# Demo python app

This is just a python playground to get to understand the python ecosystem.

## Installation

This presumes you already have python installed in your system.

This project uses [poetry](https://python-poetry.org/) a Python packaging and dependency management tool. 

Install poetry

``` bash
curl -sSL https://install.python-poetry.org | python3 -

```

Test poetry is installed:

```bash
poetry --version
```

install poetry packages:

```bash
poetry install
```

## Tests

Pytest is the testing library chosen.

To run the test: 

```bash
poetry run pytest
```


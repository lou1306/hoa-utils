## Disclaimer

This repository is a fork of `hoa-utils` (https://github.com/whitemech/hoa-utils).
I sincerely hope the (limited) changes I suggest are merged upstream. In case this
happens, I will archive the repository/PyPI package and redirect users towards the
upstream repo.

## Original README.md

Utilities for the HOA format.

## Install

The best way is to install the package from PyPI:
```
pip install hoa-utils
```

Alternatively, you can install it from source (master branch):
```
pip install git+https://github.com/whitemech/hoa-utils.git
```

## What you'll find

- APIs to create and manipulate HOA objects
- CLI tools to about the HOA format.

The implementation may not be very stable at the moment.

Currently, the only supported CLI tool is:
- `pyhoafparser`: parse and validate a file in HOA format. 


## Development

If you want to contribute, here's how to set up your development environment.

- Install [Poetry](https://python-poetry.org/)
- Clone the repository: `git clone https://github.com/whitemech/hoa-utils.git && cd hoa-utils`
- Install the dependencies: `poetry install`

## Tests

To run tests: `tox`

To run only the code tests: `tox -e py3.7`

To run only the code style checks:
 - `tox -e black-check`
 - `tox -e isort-check`
 - `tox -e flake8`
 
 In `tox.ini` you can find all the test environment supported.

## Docs

To build the docs: `mkdocs build`

To view documentation in a browser: `mkdocs serve`
and then go to [http://localhost:8000](http://localhost:8000)

## Authors

- [Marco Favorito](https://marcofavorito.github.io/)
- [Francesco Fuggitti](https://francescofuggitti.github.io/)

## License

`hoa-utils` is released under the MIT License.

Copyright 2020 WhiteMech

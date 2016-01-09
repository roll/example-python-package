# <name>

[![Travis](https://img.shields.io/travis/okfn/placeholder.svg)](https://travis-ci.org/okfn/placeholder)
[![Coveralls](http://img.shields.io/coveralls/okfn/placeholder.svg?branch=master)](https://coveralls.io/r/okfn/placeholder?branch=master)

Change all `<.*>` etc placeholders corresponding to your package metadata (for examples `ag '<.*>'` to find all of them). Almost all repository files are generic. So it could be copied
from project to project without any change.

## Usage

This section is intended to be used by end-users of the library.

## Development

This section is intended to be used by tech users collaborating
on this project.

### Getting Started

To activate virtual environment, install
dependencies, add pre-commit hook to review and test code
and get `run` command as unified developer interface:

```
$ source activate.sh
```

### Reviewing

The project follow the next style guides:
- [PEP 8 - Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

To check the project against Python style guide:

```
$ run review
```

### Testing

To run tests with coverage check:

```
$ run test
```

Coverage data will be in the `.coverage` file.

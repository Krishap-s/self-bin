# self-bin

[![PyPI](https://img.shields.io/pypi/v/self-bin.svg)](https://pypi.org/project/self-bin/)
[![Changelog](https://img.shields.io/github/v/release/Krishap-s/self-bin?include_prereleases&label=changelog)](https://github.com/Krishap-s/self-bin/releases)
[![Tests](https://github.com/Krishap-s/self-bin/actions/workflows/test.yml/badge.svg)](https://github.com/Krishap-s/self-bin/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/Krishap-s/self-bin/blob/master/LICENSE)

Self Hosted Request Bin and HTTP Bin

## Installation

Install this tool using `pip`:

    pip install self-bin

## Usage

For help, run:

    self-bin --help

You can also use:

    python -m self_bin --help

## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:

    cd self-bin
    python -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest

## TODO
- [ ] Implement request bin functionality
- [ ] Implement http bin functionality
- [ ] Allow user to control using command flags
- [ ] Update documentation

# llm-openhands

[![PyPI](https://img.shields.io/pypi/v/llm-openhands.svg)](https://pypi.org/project/llm-openhands/)
[![Changelog](https://img.shields.io/github/v/release/ftnext/llm-openhands?include_prereleases&label=changelog)](https://github.com/ftnext/llm-openhands/releases)
[![Tests](https://github.com/ftnext/llm-openhands/actions/workflows/test.yml/badge.svg)](https://github.com/ftnext/llm-openhands/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/ftnext/llm-openhands/blob/main/LICENSE)



## Installation

Install this plugin in the same environment as [LLM](https://llm.datasette.io/).
```bash
llm install llm-openhands
```
## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd llm-openhands
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
python -m pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```

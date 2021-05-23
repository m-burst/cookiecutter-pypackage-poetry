# {{ cookiecutter.project_name }}

[![pypi](https://badge.fury.io/py/{{cookiecutter.project_name}}.svg)](https://pypi.org/project/{{cookiecutter.project_name}})
[![Python: 3.6+](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://pypi.org/project/{{cookiecutter.project_name}})
[![Downloads](https://img.shields.io/pypi/dm/{{cookiecutter.project_name}}.svg)](https://pypistats.org/packages/{{cookiecutter.project_name}})
[![Build Status](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/actions/workflows/ci.yml)
[![Code coverage](https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/branch/master/graph/badge.svg)](https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_name}})
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://en.wikipedia.org/wiki/MIT_License)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

## Description

{{ cookiecutter.description }}

## Installation

    pip install {{ cookiecutter.project_name }}

## Usage

...

## For developers

### Install deps and setup pre-commit hook

    make init

### Run linters, autoformat, tests etc.

    make format lint test

### Bump new version

    make bump_major
    make bump_minor
    make bump_patch

## License

MIT

## Change Log

**Unreleased**

* initial

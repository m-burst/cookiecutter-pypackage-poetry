# cookiecutter-pypackage-poetry

The cookicutter template of a python package with poetry, travis, etc.

## Usage

### Create project

```bash
$ cookiecutter gh/m-burst/cookiecutter-pypackage-poetry
project_name []: my_project
full_name []: John Doe
email []: john_doe@gmail.com
github_username []: john_doe
Select use_travis:
1 - yes
2 - no
Choose from 1, 2 (1, 2) [1]: 1
```

### Install deps and setup pre-commit hook

    make init

### Run linters, autoformat, tests etc.

    make format lint test

### Bump new version

    make bump_major
    make bump_minor
    make bump_patch

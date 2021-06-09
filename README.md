# Project_Name

> Template based on https://github.com/piotlinski/python-project-template

## Development

Rename your project in Makefile, Readme.md, pyproject.toml, and folder name

Requirements:

- Install `pre-commit` (https://pre-commit.com/#install)
- Install `poetry` (https://python-poetry.org/docs/#installation)
- Execute `pre-commit install`
- Use `poetry` to handle requirements

  - Execute `poetry add <package_name>` to add new library
  - Execute `poetry install` to create virtualenv and install packages

- For Pycharm use plugin to run poetry env based on totml file (Poetry)

Using Make:

Use `make` to run commands

- `make help` - show help
- `make format` - format code
- `make test` - run tests
  - `args="--lf" make test` - run pytest tests with different arguments
- `make shell` - run poetry shell
- `make docs` - automatically make documentation

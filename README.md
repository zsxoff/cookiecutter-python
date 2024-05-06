# Cookiecutter Python

[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a Python project.

- GitHub repo: <https://github.com/zsxoff/cookiecutter-python>

## Quickstart

Install the Cookiecutter via [pipx](https://github.com/pypa/pipx):

```bash
pipx install cookiecutter
```

or via pip:

```bash
python -m pip install --user cookiecutter
```

Generate a Python project:

```bash
cookiecutter https://github.com/zsxoff/cookiecutter-python.git
```

## Make changes in this project

Use `venv` for development:

```bash
mkdir -p .venv && python3 -m venv .venv
```

Install development packages:

```bash
pip install -r requirements-dev.txt
```

Install [pre-commit](https://github.com/pre-commit/pre-commit):

```bash
pre-commit install
```

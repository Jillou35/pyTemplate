# {{ cookiecutter.project_name }}

[![CI](https://github.com/{{ cookiecutter.author_name }}/{{ cookiecutter.project_slug }}/actions/workflows/ci.yml/badge.svg)](https://github.com/{{ cookiecutter.author_name }}/{{ cookiecutter.project_slug }}/actions/workflows/ci.yml)
[![Coverage](https://raw.githubusercontent.com/{{ cookiecutter.author_name }}/{{ cookiecutter.project_slug }}/badges/coverage.svg)](https://github.com/{{ cookiecutter.author_name }}/{{ cookiecutter.project_slug }}/tree/badges)
[![Python Version](https://img.shields.io/badge/python-{{ cookiecutter.python_version }}+-blue.svg)](https://www.python.org/downloads/)
[![Code Style: ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Checked with mypy](https://www.mypy-lang.org/static/mypy_badge.svg)](https://mypy-lang.org/)

{{ cookiecutter.description }}

## 🚀 Features

- **Package Manager**: [uv](https://github.com/astral-sh/uv) - Extremely fast Python package installer and resolver.
- **Linting & Formatting**: [Ruff](https://github.com/astral-sh/ruff) - Blazing fast Python linter and formatter.
- **Type Checking**: [MyPy](https://mypy-lang.org/) - Strict static typing.
- **Testing**: [Pytest](https://docs.pytest.org/) + coverage
- **Security**: [Ruff](https://docs.astral.sh/ruff/rules/#flake8-bandit-s) (Bandit rules)
- **Documentation**: [Interrogate](https://interrogate.readthedocs.io/) (Docstring coverage)
- **CI/CD**: GitHub Actions workflow included
- **Automation**: [Makefile](Makefile) & [GitHub Actions](.github/workflows/ci.yml).

## 🛠️ Installation

Ensure you have `uv` installed:

```bash
pip install uv
# or
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Install dependencies:

```bash
uv sync
```

## 👩‍💻 Usage

Description of how to use the project.

## 🧪 Testing & Linting

Run linting and static analysis:

```bash
uv run task lint
```

Run tests:

```bash
uv run task test
```

Format code:

```bash
uv run task format
```

Run everything (check):

```bash
uv run task check
```

Security Audit:

```bash
uv run task audit
```

Check Documentation:

```bash
uv run task docs
```

Build package:

```bash
uv run task build
```

Deploy to PyPI:

```bash
uv run task deploy
```

Deploy to TestPyPI:

```bash
uv run task test-deploy
```

## 📄 License

This project is licensed under the MIT License.

# PyTemplate

A modern, "Zero Friction" and "Full Quality" Cookiecutter template for Python 3.12+ projects.

Designed to get you up and running instantly with a production-ready development environment.

## 🚀 Features

- **Dependency Management**: [uv](https://github.com/astral-sh/uv) (Blazing fast!)
- **Linting & Formatting**: [Ruff](https://github.com/astral-sh/ruff)
- **Static Typing**: [MyPy](https://mypy-lang.org/) (Strict mode)
- **Testing**: [Pytest](https://docs.pytest.org/) + coverage
- **Security**: [Ruff](https://docs.astral.sh/ruff/rules/#flake8-bandit-s) (Bandit rules) + [pip-audit](https://github.com/pypa/pip-audit) (dependency audit)
- **Documentation**: [Interrogate](https://interrogate.readthedocs.io/)
- **CI/CD**: GitHub Actions workflow included
- **Automation**: [Taskipy](https://github.com/taskipy/taskipy)

## 📦 Usage

You can generate a new project directly from this template directory.

### Prerequisites

You need `cookiecutter` installed. If you are using `uv`:

```bash
uv tool install cookiecutter
```

### Formatting a new project

Run cookiecutter against the template directory (`pytemplate`):

```bash
uvx cookiecutter ./pytemplate
```

Follow the prompts to configure your project name, author, etc.

## 🛠️ Generated Project Commands

Once your project is generated, you can use `uv` directly:

```bash
cd <your-project-slug>
uv sync            # Install dependencies
uv run task check  # Run all the following checks
uv run task format # Run formatting
uv run task lint   # Run linting
uv run task audit  # Run security audit
uv run task docs   # Run documentation checks
uv run task test   # Run tests individually
```

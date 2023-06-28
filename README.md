## Template For Python Projects

This is a template for Python projects. What you get:

- Source code and test code is seperated in different directories.
- External libraries installed and managed by [Pip](https://pypi.org/project/pip/) and [setuptools](https://setuptools.pypa.io/en/latest/) in a pyproject.toml.
- Setup for tests using [Pytest](https://docs.pytest.org/en/stable/) and coverage with [Pytest-Cov](https://github.com/pytest-dev/pytest-cov).
- Code coverage reports, including automatic upload to [Codecov](https://codecov.io).

### Commands

```bash
# Build and Install (local)
pip install -e .  # OR
pip install -e ../Python-Project-Template  # OR
pip install -e ../Python-Project-Template[all]
```

```bash
# Test
pytest tests  # OR
pytest .  # OR
pytest
```

```bash
# Code Coverage
pytest --cov=fastvector tests --cov-report=html
```

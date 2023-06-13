# Awesome pre-commit [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
A curated list of awesome pre-commit hooks.

> [pre-commit](https://pre-commit.com/ ) is a framework for managing and maintaining multi-language pre-commit hooks.

## Pre-commit hooks

### Python
<details>
  <summary>Bandit: a tool designed to find common security issues in Python code</summary>
  
  ##### Links
  - GitHub repository: [bandit](https://github.com/PyCQA/bandit)
  - Documentation: [here](https://bandit.readthedocs.io/en/latest/)
  ##### Example
  ```yaml
  repos:
  - repo: https://github.com/PyCQA/bandit
    rev: '1.7.5' # Update me!
    hooks:
    - id: bandit
  ```
</details>
<details>
  <summary>Black: the uncompromising Python code formatter</summary>
  
  ##### Links
  - GitHub repository: [black](https://github.com/psf/black)
  - Documentation: [here](https://black.readthedocs.io/en/stable/)
  ##### Example
  ```yaml
  repos:
  - repo: https://github.com/psf/black
    rev: 23.3.0
    hooks:
      - id: black
        # It is recommended to specify the latest version of Python
        # supported by your project here, or alternatively use
        # pre-commit's default_language_version, see
        # https://pre-commit.com/#top_level-default_language_version
        language_version: python3.9
  ```
</details>
<details>
  <summary>Mypy: optional static typing for Python </summary>
  
  ##### Links
  - GitHub repository: [mypy](https://github.com/pre-commit/mirrors-mypy)
  - Documentation: [here](https://mypy.readthedocs.io/en/stable/)
  ##### Example
  ```yaml
  - repo: https://github.com/pre-commit/mirrors-mypy
    rev: 'v1.3.0'  # Use the sha / tag you want to point at
    hooks:
    - id: mypy
  ```
</details>
<details>
  <summary>Ruff: an extremely fast Python linter, written in Rust.</summary>
  
  ##### Links
  - GitHub repository: [ruff](https://github.com/astral-sh/ruff)
  - Documentation: [here](https://beta.ruff.rs/docs/)
  ##### Example
  ```yaml
  repos:
    - repo: https://github.com/astral-sh/ruff-pre-commit
    # Ruff version.
    rev: v0.0.272
    hooks:
    - id: ruff
  ```
</details>

  

# Awesome pre-commit [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
A curated list of awesome pre-commit hooks.

> [pre-commit](https://pre-commit.com/ ) is a framework for managing and maintaining multi-language pre-commit hooks.

## Pre-commit hooks

### Python
<details>
  <summary>Black: The uncompromising Python code formatter</summary>
  
  #### Github Repository: [black](https://github.com/psf/black)
  #### Example
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

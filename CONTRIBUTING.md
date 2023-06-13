# Contribution Guidelines
Contributions are always welcome! However, please follow these guidelines to make it as smooth as possible.

## Guidelines
- Submit one pull request per pre-commit hook you want to add to this list.
- Your pull request title should be formatted like `Add name-of-pre-commit-hook`.
- Use the template below when adding a new pre-commit hook to the list.
## Template
Copy the example below and paste it into [README.md](README.md) wherever you want to add a new pre-commit hook.
Edit relevant fields:
- summary: name of the package + brief summary.
- GitHub repository: link to the package repository.
- Documentation: link to the package documentation.
- Example: can usually be found in the package documentation or README.
````
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
````

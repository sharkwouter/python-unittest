# Pre-commit hook for Python based unit tests

A hook for running `python3 -m unittest discover` within your project upon running `git commit` using [pre-commit](https://pre-commit.com/).

## Using with pre-commit

Simply add the following to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/sharkwouter/python-unittest
    rev: 1.0
    hooks:
    -   id: python-unittest
```


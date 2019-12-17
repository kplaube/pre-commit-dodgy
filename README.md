# pre-commit-dodgy

A pre-commit hook to help you avoid dodgy things on your Python project.

For pre-commit: see https://github.com/pre-commit/pre-commit

For dodgy: see https://github.com/landscapeio/dodgy

## Using dodgy with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
  repos:
    - repo: https://github.com/kplaube/pre-commit-dodgy
      rev: "0.0.1" . # Use `master` for the latest version
      hooks:
        - id: dodgy
```

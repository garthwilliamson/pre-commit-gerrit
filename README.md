# Gerrit Commit Message Hook (for pre-commit)

## Setup

See [Pre-commit documentation](https://pre-commit.com/#adding-pre-commit-plugins-to-your-project).

## Supported Hooks

### gerrit-commit-msg

```yaml
- repo: https://github.com/garthwilliamson/pre-commit-gerrit.git
  rev: v0.1.1
  hooks:
  - id: gerrit-commit-msg
```

Adds the gerrit change-id to the commit message.

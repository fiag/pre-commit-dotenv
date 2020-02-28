# pre-commit-dotenv

dotenv-linter pre-commit.com hook

## Install

See <https://github.com/mgrachev/dotenv-linter#-installation>.

## Pre-commit hook

Sample `.pre-commit-config.yaml`:

```
-   repo: https://github.com/fiag/pre-commit-dotenv
    rev: v1.0.0
    hooks:
    -   id: dotenv-linter
```

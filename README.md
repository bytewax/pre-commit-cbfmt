# Pre-commit hooks for cbfmt

[cbfmt](https://github.com/lukas-reineke/cbfmt) tools package for [pre-commit](https://pre-commit.com).

## Using cbfmt tools with pre-commit

```yaml
-   repo: https://github.com/bytewax/cbfmt-pre-commit
    rev: main
    hooks:
    -   id: fmt
```

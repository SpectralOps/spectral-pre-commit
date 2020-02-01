# Spectral `pre-commit` Integration

This is a repo with Spectral hooks for [pre-commit](https://pre-commit.com/)

## Usage

If you want to add Spectral to your Git pre-commit hooks and you're using [pre-commit](https://pre-commit.com/), you can add the following to your `.pre-commit-config.yaml`:

```yaml
repos:
-   repo: https://github.com/spectralops/spectral-pre-commit
    rev: master
    hooks:
    - id: spectral
```

See [spectralops/spectral-example-pre-commit](https://github.com/SpectralOps/spectral-example-pre-commit) for a living example.

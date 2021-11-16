# Spectral `pre-commit` Integration

This is a repo with Spectral hooks for [pre-commit](https://pre-commit.com/)

## Usage

To use Spectral you need an active Spectral account. If you don't have one yet, [grab a free trial](https://get.spectralops.io)!

If you want to add Spectral to your Git pre-commit hooks and you're using [pre-commit](https://pre-commit.com/):

1. Add the following to your `.pre-commit-config.yaml`:
    ```yaml
    repos:
    -   repo: https://github.com/spectralops/spectral-pre-commit
        rev: master
        hooks:
        - id: spectral
    ```
2. Make sure you have the spectral executable in your PATH. 
3. Make sure you have your Spectral DSN (`spk-xxx`) as an env var.

See [spectralops/spectral-example-pre-commit](https://github.com/SpectralOps/spectral-example-pre-commit) for a live example.

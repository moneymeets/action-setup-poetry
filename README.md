# action-setup-poetry
GitHub action for setting up Poetry


# Usage

See [action.yml](action.yml).

Basic:
```yaml
steps:
    - name: Setup Poetry
      uses: moneymeets/action-setup-poetry@master
```

With specific version:
```yaml
steps:
    - name: Setup Poetry
      uses: moneymeets/action-setup-poetry@master
      with:
        version: 1.1.4
```

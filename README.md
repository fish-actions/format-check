# format-check [![license_badge][]][license]

A simple action to check the formatting of all fish files in your repository.

## Usage

```yml
format-check:
  runs-on: ubuntu-latest

  steps:
    - uses: actions/checkout@v2

    - uses: fish-actions/install-fish@v1

    - uses: fish-actions/format-check@v1
```

[license_badge]: https://img.shields.io/github/license/fish-actions/format-check
[license]: LICENSE.md

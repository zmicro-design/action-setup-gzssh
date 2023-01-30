# GitHub Action to setup GZSSH

![https://github.com/zmicro-design/action-setup-gzssh](https://img.shields.io/github/v/release/zmicro-design/action-setup-gzssh)
![https://github.com/zmicro-design/action-setup-gzssh](https://github.com/zmicro-design/action-setup-gzssh/workflows//Publish/badge.svg)

### Usage

| option | required | description |
| ------ | -------- | ----------- |

### Example

```yml
# Setup Web Terminal CLI only
name: CI

on: [push]

jobs:
  build:
    name: Test
    runs-on: ubuntu-latest
    steps:
      - name: Setup Web Terminal
        uses: zmicro-design/action-setup-gzssh@v1
```

### License

[MIT](./LICENSE)

# shibui-sample-action
Sample GitHub Actions

# Usage

```yaml
name: Test

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  tests:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: sample
        uses: shibuiwilliam/sample-actions@v1
```

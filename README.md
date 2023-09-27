# ryunixjs-action

### Usage

```yml
name: Deploy RyunixJS site to Pages

on:
  push:
    branches:
      - "main" # rename if is necessary 

permissions:
  contents: read
  pages: write
  id-token: write

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
    - id: build-publish
      uses: UnSetSoft/ryunixjs-actions@v1.0.0
```

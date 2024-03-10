# Docker Utils

[![Build Images](https://github.com/Ilyes512/utils/actions/workflows/main.yml/badge.svg)](https://github.com/Ilyes512/utils/actions/workflows/main.yml)

A minimal Alpine based image with:

- bash (set as default shell for root user)
- curl
- wget
- jq
- yq
- sed
- pcre-tools
- ssh-keygen

## Task

This project uses [Task](https://taskfile.dev) (an task runner / build tool).

Available tasks for this project:

```
* build:               Build the Utils image
* lint:                Apply a Dockerfile linter (https://github.com/hadolint/hadolint)
* shell:               Interactive shell
* list:packages:       List all installed packages
```

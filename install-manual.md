# How to install and convert this CV

## Prequisite
- Docker

## Procedure

1. Convert markdown CV to HTML formats

```sh
docker run --rm --volume "`pwd`:/data" --user `id -u`:`id -g` pandoc/latex:2.6 README.md > README.html
```
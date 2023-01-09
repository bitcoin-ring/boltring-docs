# BoltRing Documentation

*Source code for BoltRing documentation static site*

## Introduction

This repository hosts the markdown based documentation and mkdocs based static site builder for
https://docs.bolt-ring.com.

## Development

### Requirements

- [Python 3.7](https://www.python.org/) or higher for static site building and publishing.
- [Poetry](https://python-poetry.org/) for installation and dependency management.

### Installation

```shell
git clone https://github.com/bitcoin-ring/boltring-docs.git
cd boltring-docs
poetry install
```

### Running

To start the developmnet server run:

```shell
mkdocs serve
```

### Tasks

Before committing any changes you should run all formatting tasks with

```shell
poe all
```

### Publishing

To publish the latest version the site run:

```shell
mkdocs gh-deploy
```

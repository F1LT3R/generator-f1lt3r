# generator-f1lt3r

> Quick setup for Node Modules.

## What is Included?

- XO Code Style and linting
- AVA - The Futuristic Test Runner
- NYC - Istanbul Coverage
- Coveralls.io - Coverage Reports

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

This is what I use for [my own Node modules](https://www.npmjs.com/~f1lt3r).

Based on [generator-nm](https://raw.githubusercontent.com/sindresorhus/generator-nm) by [sindresorhus](https://www.npmjs.com/~sindresorhus).

## Install

```shell
yarn global add yo generator-f1lt3r
```

## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo nm
```

There are multiple command-line options available:

```
$ yo nm --help

  Usage:
    yo nm [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
```

The `--org` option takes a string value (i.e. `--org=my-org`).
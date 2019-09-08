mynewcli
========

next gen cli

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/mynewcli.svg)](https://npmjs.org/package/mynewcli)
[![CircleCI](https://circleci.com/gh/tauheedkhan/node-demo-cli.svg?style=svg&circle-token=85a83ae2872cd62f48631474f35609656647a498)](https://circleci.com/gh/tauheedkhan/node-demo-cli)
[![Codecov](https://codecov.io/gh/tauheedkhan/mynewcli/branch/master/graph/badge.svg)](https://codecov.io/gh/tauheedkhan/mynewcli)
[![Downloads/week](https://img.shields.io/npm/dw/mynewcli.svg)](https://npmjs.org/package/mynewcli)
[![License](https://img.shields.io/npm/l/mynewcli.svg)](https://github.com/tauheedkhan/mynewcli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g mynewcli
$ mynewcli COMMAND
running command...
$ mynewcli (-v|--version|version)
mynewcli/0.0.0 darwin-x64 node-v8.16.0
$ mynewcli --help [COMMAND]
USAGE
  $ mynewcli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`mynewcli hello`](#mynewcli-hello)
* [`mynewcli help [COMMAND]`](#mynewcli-help-command)

## `mynewcli hello`

Describe the command here

```
USAGE
  $ mynewcli hello

OPTIONS
  -n, --name=name  name to print

DESCRIPTION
  ...
  Extra documentation goes here
```

_See code: [src/commands/hello.js](https://github.com/tauheedkhan/mynewcli/blob/v0.0.0/src/commands/hello.js)_

## `mynewcli help [COMMAND]`

display help for mynewcli

```
USAGE
  $ mynewcli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src/commands/help.ts)_
<!-- commandsstop -->

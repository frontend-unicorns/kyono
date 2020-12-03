kyono
=====

A cross-platform native bridge for web apps

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/kyono.svg)](https://npmjs.org/package/kyono)
[![Downloads/week](https://img.shields.io/npm/dw/kyono.svg)](https://npmjs.org/package/kyono)
[![License](https://img.shields.io/npm/l/kyono.svg)](https://github.com/frontend-unicorns/kyono/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g kyono
$ kyono COMMAND
running command...
$ kyono (-v|--version|version)
kyono/0.0.0 darwin-x64 node-v12.16.0
$ kyono --help [COMMAND]
USAGE
  $ kyono COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`kyono hello [FILE]`](#kyono-hello-file)
* [`kyono help [COMMAND]`](#kyono-help-command)

## `kyono hello [FILE]`

describe the command here

```
USAGE
  $ kyono hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ kyono hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/frontend-unicorns/kyono/blob/v0.0.0/src/commands/hello.ts)_

## `kyono help [COMMAND]`

display help for kyono

```
USAGE
  $ kyono help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->

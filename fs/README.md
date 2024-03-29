fs
==

fs cli to build the platform

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/fs.svg)](https://npmjs.org/package/fs)
[![Downloads/week](https://img.shields.io/npm/dw/fs.svg)](https://npmjs.org/package/fs)
[![License](https://img.shields.io/npm/l/fs.svg)](https://github.com/FuncStack/fs-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g fs
$ fs COMMAND
running command...
$ fs (-v|--version|version)
fs/0.0.1 darwin-x64 node-v10.16.0
$ fs --help [COMMAND]
USAGE
  $ fs COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`fs hello [FILE]`](#fs-hello-file)
* [`fs help [COMMAND]`](#fs-help-command)

## `fs hello [FILE]`

describe the command here

```
USAGE
  $ fs hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ fs hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/FuncStack/fs-cli/blob/v0.0.1/src/commands/hello.ts)_

## `fs help [COMMAND]`

display help for fs

```
USAGE
  $ fs help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.0/src/commands/help.ts)_
<!-- commandsstop -->

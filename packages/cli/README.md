# bara

Created to create any system with the power of words.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io) [![Version](https://img.shields.io/npm/v/bara.svg)](https://npmjs.org/package/bara) [![CircleCI](https://circleci.com/gh/barajs/bara/tree/master.svg?style=shield)](https://circleci.com/gh/barajs/bara/tree/master) [![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/barajs/bara?branch=master&svg=true)](https://ci.appveyor.com/project/barajs/bara/branch/master) [![Codecov](https://codecov.io/gh/barajs/bara/branch/master/graph/badge.svg)](https://codecov.io/gh/barajs/bara) [![Downloads/week](https://img.shields.io/npm/dw/bara.svg)](https://npmjs.org/package/bara) [![License](https://img.shields.io/npm/l/bara.svg)](https://github.com/barajs/bara/blob/master/package.json)

<!-- toc -->

- [bara](#bara)
- [Usage](#usage)
- [Commands](#commands)
  <!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g bara
$ bara COMMAND
running command...
$ bara (-v|--version|version)
bara/0.1.0 darwin-x64 node-v10.9.0
$ bara --help [COMMAND]
USAGE
  $ bara COMMAND
...
```

<!-- usagestop -->

# Commands

<!-- commands -->

- [`bara backend [FILE]`](#bara-backend-file)
- [`bara help [COMMAND]`](#bara-help-command)

## `bara backend [FILE]`

Create a backend service

```
USAGE
  $ bara backend [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ bara backend
  create backend service
```

_See code: [src/commands/backend.ts](https://github.com/barajs/bara/blob/v0.1.0/packages/cli/src/commands/backend.ts)_

## `bara help [COMMAND]`

display help for bara

```
USAGE
  $ bara help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.2/src/commands/help.ts)_

<!-- commandsstop -->

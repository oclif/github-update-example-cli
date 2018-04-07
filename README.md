@oclif/github-update-example-cli
=================================

example of using @oclif/plugin-update with github releases

[![Version](https://img.shields.io/npm/v/@oclif/github-update-example-cli.svg)](https://npmjs.org/package/@oclif/github-update-example-cli)
[![CircleCI](https://circleci.com/gh/oclif/github-update-example-cli/tree/master.svg?style=shield)](https://circleci.com/gh/oclif/github-update-example-cli/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/oclif/github-update-example-cli?branch=master&svg=true)](https://ci.appveyor.com/project/oclif/github-update-example-cli/branch/master)
[![Codecov](https://codecov.io/gh/oclif/github-update-example-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/oclif/github-update-example-cli)
[![Downloads/week](https://img.shields.io/npm/dw/@oclif/github-update-example-cli.svg)](https://npmjs.org/package/@oclif/github-update-example-cli)
[![License](https://img.shields.io/npm/l/@oclif/github-update-example-cli.svg)](https://github.com/oclif/github-update-example-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @oclif/github-update-example-cli
$ github-cli COMMAND
running command...
$ github-cli (-v|--version|version)
@oclif/github-update-example-cli/0.0.0 darwin-x64 node-v9.11.1
$ github-cli --help [COMMAND]
USAGE
  $ github-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [github-cli hello [FILE]](#github-cli-hello-file)
* [github-cli help [COMMAND]](#github-cli-help-command)

## github-cli hello [FILE]

describe the command here

```
USAGE
  $ github-cli hello [FILE]

OPTIONS
  -f, --force
  -n, --name=name  name to print

EXAMPLE
  $ github-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/oclif/github-update-example-cli/blob/v0.0.0/src/commands/hello.ts)_

## github-cli help [COMMAND]

display help for github-cli

```
USAGE
  $ github-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v1.2.3/src/commands/help.ts)_
<!-- commandsstop -->

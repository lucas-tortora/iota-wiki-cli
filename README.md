iota-wiki-cli
========

This utility requires [`yarn`](https://yarnpkg.com/) and [`git`](https://git-scm.com/) to be installed.

Configure the utility with a config json. See a example [`here`](./config.example.json).

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g iota-wiki-cli
$ iota-wiki-cli COMMAND
running command...
$ iota-wiki-cli (-v|--version|version)
iota-wiki-cli/1.4.0 linux-x64 node-v14.16.1
$ iota-wiki-cli --help [COMMAND]
USAGE
  $ iota-wiki-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`iota-wiki-cli checkout`](#iota-wiki-cli-checkout)
* [`iota-wiki-cli clean`](#iota-wiki-cli-clean)
* [`iota-wiki-cli help [COMMAND]`](#iota-wiki-cli-help-command)
* [`iota-wiki-cli setup`](#iota-wiki-cli-setup)
* [`iota-wiki-cli start`](#iota-wiki-cli-start)

## `iota-wiki-cli checkout`

checkout content repositories

```
USAGE
  $ iota-wiki-cli checkout

OPTIONS
  -h, --help            show CLI help
  -o, --[no-]overwrite  Disable/Enable overwriting of static content

EXAMPLE
  $ iota-wiki-cli checkout
```

## `iota-wiki-cli clean`

completely removes local wiki

```
USAGE
  $ iota-wiki-cli clean

OPTIONS
  -h, --help  show CLI help
```

## `iota-wiki-cli help [COMMAND]`

display help for iota-wiki-cli

```
USAGE
  $ iota-wiki-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_

## `iota-wiki-cli setup`

setup local wiki

```
USAGE
  $ iota-wiki-cli setup

OPTIONS
  -h, --help     show CLI help
  -r, --ref=ref  wiki revison to checkout

EXAMPLE
  $ iota-wiki-cli setup --ref main
```

## `iota-wiki-cli start`

start local wiki

```
USAGE
  $ iota-wiki-cli start

OPTIONS
  -h, --help  show CLI help
```
<!-- commandsstop -->

# git-verbose

`git-verbose` is a git extension that provides a more verbose output for some git commands.


## Installation

Just copy the `git-verbose` file to a directory in your `$PATH`.

## Usage

`git-verbose` is a git extension, so it is used as a git command.\
It is used as a prefix to the git command you want to run. For example, to run `git init` with verbose output, you would run `git verbose init`.

## Commands

### init
```console
$ git verbose init
```

### add
```console
$ git verbose add <file>
```

### commit
```console
$ git verbose commit -m <message>
```

### tag
```console
$ git verbose tag <tag_name> <tag_message>
```



# My github WorkFlow

## Github Cli Extensions

primero vamos a instalar algunas gh extensiones para luego agregarlas a nuestros alias

https://github.com/yusukebe/gh-markdown-preview

## Installation

```
gh extension install yusukebe/gh-markdown-preview
```

## Usage

The usage:

```
gh markdown-preview README.md
```

Or this command will detect README file in the directory automatically.

```
gh markdown-preview
```

https://github.com/vilmibm/gh-screensaver

## installation

```
gh extension install vilmibm/gh-screensaver
```

## usage

- `gh screensaver` run a random screensaver
- `gh screensaver -s pipes` run a screensaver by name
- `gh screensaver -l` list available screensavers

Extra configuration options can be passed after a `--`; for example:

```
gh screensaver -smarquee -- --message="hello world" --font="script"
```

https://github.dev/korosuke613/gh-user-stars

Please follow their installation instructions if you don't have them yet.

Then, install this extension by running:

```
gh extension install korosuke613/gh-user-stars
```

## Usage

```
❯ gh user-stars -h

Displays an interactive list of your starred repositories.
The URL of the selected repository is printed as the output of the command.

Dependencies: fzf, jq

Usage
  gh user-stars [NUMBER]

NUMBER: Number of stars to fetch at a time. (default: 50, max: 100)
```

https://github.com/kawarimidoll/gh-graph

## Installation

```
gh extension install kawarimidoll/gh-graph
```

### Upgrading

```
gh extension list
gh extension upgrade kawarimidoll/gh-graph
```

## Usage

Simply run:

```
gh graph
```

View the help:

```
gh graph --help
```

Have fun:

```
gh graph --pixel %EF%90%88%20 --scheme unicorn
```

https://github.com/chelnak/gh-changelog

## What is supported?

`gh-changelog` is the tool for you if:

- You want to closely follow the [keep a changelog](https://keepachangelog.com/en/1.0.0/) specification
- You are using tags to mark releases
- You are following a pull-request workflow

Here is an overview of the pull request workflow: 0. “Pull” the changes to your local machine (get the most recent base)

1. Create a “branch” (version)
2. Commit the changes
   3.a Push your changes
   3.b Open a “pull request” (propose changes)
3. Discuss and review your code
4. Rebase and tests
5. “Merge” your branch to the master branch

## Installation and Usage

Before you start make sure that:

- GitHub Cli is [installed](https://cli.github.com/manual/installation) and [authenticated](https://cli.github.com/manual/gh_auth_login)
- You are inside a git repository
- The repository contains commits and has been pushed to GitHub

### Install

```bash
gh extension install chelnak/gh-changelog
```

### Upgrade

```bash
gh extension upgrade chelnak/gh-changelog
```

### Create a changelog

Creating changelog is simple.
Once you have installed the extension just run:

```bash
gh changelog new
```



https://github.com/mislav/gh-cp



```bash
gh extension install mislav/gh-cp
```
A GitHub CLI extension to copy a file from a GitHub repository locally without cloning the repository.

```sh
$ gh extension install mislav/gh-cp

$ gh cp
Usage: gh cp <repo> <path> <dest>

$ gh cp cli/cli pkg/findsh/find_windows.go .

```

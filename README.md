[CHANGELOG]: ./CHANGELOG.md

# Snips

<!-- Badges:Begin -->
[![Automate Changelog](https://github.com/jimbrig/snips/actions/workflows/changelog.yml/badge.svg)](https://github.com/jimbrig/snips/actions/workflows/changelog.yml)
<!-- Badges:End -->

> **Note** This repository houses code-snippets for various tasks using the [snips-cli](https://github.com/srijanshetty/snips) command-line tool.

## Contents

<details>
<summary>Table of Contents</summary>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Installation](#installation)
- [Usage](#usage)
- [Snippets](#snippets)
  - [Linux](#linux)
  - [Windows](#windows)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

</details>

## Installation

This project depends on [snips-cli](https://github.com/srijanshetty/snips):

```bash
npm install -g snips-cli
```

## Usage

```bash
snips                           # with no arguments it will just list all your snips.
snips list                      # lists all your snips.
snips new <snip-name>           # create <snip-name> snip
snips edit <snip-name?>         # edit <snip-name> snip, fuzzy completion if snip-name is skipped
snips copy <snip-name?>         # Copies content of the snip to the clipboard, fuzzy completion if snip-name is skipped
```

## Snippets

All snips are stored in `~/.snips` directory. 

### Linux

- [`install-poetry`](linux/install-poetry): Installs [poetry](https://python-poetry.org/) - a Python dependency management and packaging tool.

- [`list-shells`](linux/list-shells): uses `/etc/passwd` to get a list of available shells

### Windows

- [`checkdisk`](windows/checkdisk): Runs the Windows `chkdsk` command with optimal arguments.

- [`get-user-privileges`](windows/get-user-privileges): Runs `whoami /priv` (Windows only)

- [`new-restore-point`](windows/new-restore-point): Creates a new restore point for Windows.

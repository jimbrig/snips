[CHANGELOG]: ./CHANGELOG.md

# Snips

<!-- Badges:Begin -->
[![Automate Changelog](https://github.com/jimbrig/snips/actions/workflows/changelog.yml/badge.svg)](https://github.com/jimbrig/snips/actions/workflows/changelog.yml)
<!-- Badges:End -->

> **Note** This repository houses code-snippets for various tasks using the [snips-cli](https://github.com/srijanshetty/snips) command-line tool.

## Contents

<details>
<summary>Table of Contents</summary>

<!-- AUTO-GENERATED-CONTENT:START (TOC) -->
<!-- AUTO-GENERATED-CONTENT:END -->

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

- [checkdisk](checkdisk): Runs the Windows `chkdsk` command with optimal arguments.

- [get-user-priveledges](get-user-priveledges): Runs `whoami /priv` (Windows only)

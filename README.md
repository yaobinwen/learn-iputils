# Learn `iputils`

## Overview

This repository contains the versions of [iputils](https://launchpad.net/ubuntu/+source/iputils) source files that I'm interested in and the notes I made for learning purpose. Because I mainly work on Ubuntu, the source code all comes from the `iputils` package on Launchpad. Therefore, the code in this repository belongs to the original authors and should be used under the same license. See [their license on Launchpad](https://git.launchpad.net/ubuntu/+source/iputils/tree/LICENSE).

Each version is in its own sub-folder. My notes are all marked with `NOTE(ywen)`. The log messages I added are prefixed with `[ywen]`.

## Versions

- `3%20161105-1ubuntu3`: The version used on Ubuntu 18.04 (with patches applied). Corresponding tag: [`applied/3%2520161105-1ubuntu3`](https://git.launchpad.net/ubuntu/+source/iputils/tag/?h=applied/3%2520161105-1ubuntu3).
  - I have to replace `:` right after the epoch version with `%` (as the git tag did) because `make` doesn't seem to like `:` in the file paths. It would report "multiple target patterns" errors.

# Open Government Command Line Interface

This repo contains a shell script for the `og` command.

## Installation

1. Pull the repo into any directory
1. Add that directory into your `PATH` variable
1. Link the autocompletion script to your bash completions: `sudo ln -s  $(dirname "$(which og)")/autocomplete /etc/bash_completion.d/og` (you may need to restart your shell afterwards)
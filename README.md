# `gh prs` GitHub CLI Extension

An extension for [GitHub CLI](https://cli.github.com/) that allows you to list
and checkout pull requests.

## Installation

    gh extension install mloberg/gh-prs

To use this, you will need [fzf](https://github.com/junegunn/fzf#readme). To
intall with Homebrew:

    brew install fzf

## Usage

    gh prs

Selecting a PR will check out the PR.

You can also list PRs without an interactive prompt with the `--static` flag.

    gh prs --static

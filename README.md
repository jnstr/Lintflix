# Lintflix

A shell utility to commit the staged changes using a movie or tv-show inspired message.  

## Why?

I tend to make mistakes against the style guide so I create linting commits on a regular base. I don't like boring messages so I thought it would be fun to add movie & tv-show inspired messages, slightly adjusted to have the word "lint" somewhere.

Inspired by https://github.com/fowbi/lint-along

## Installation

1. Clone this repository
2. cd into the project directory
3. `chmod +x lintflix.sh`
4. `ln -s "$(pwd)/lintflix.sh" /usr/local/bin/lintflix`

## Usage

```shell
# Fix some linting errors
> git commit .
> lintflix
```

A new commit is created (e.g. `🚨 James Bond - Lint Another Day`)

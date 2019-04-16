# Lintflix

A shell utility to commit the staged changes using a movie or tv-show inspired message.  

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

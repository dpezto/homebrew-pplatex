# homebrew-pplatex

Homebrew tap for [pplatex](https://github.com/dpezto/pplatex), a command-line
tool that parses latex/pdflatex/lualatex logs and prints readable errors and
warnings. Maintained fork of
[stefanhepp/pplatex](https://github.com/stefanhepp/pplatex).

## Install

    brew tap dpezto/pplatex
    brew install --HEAD dpezto/pplatex/pplatex

Installs `pplatex` plus the `ppdflatex` and `ppluatex` engine aliases.

Head-only until the fork tags a release; `brew upgrade --fetch-HEAD` picks up
new commits.

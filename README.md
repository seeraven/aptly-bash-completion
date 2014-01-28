aptly-bash-completion
=====================

This is a bash completion for [aptly](http://www.aptly.info/).

## Installation

### Linux

Download bash completions to `/etc/bash_completion.d`:

    sudo wget https://github.com/aptly-dev/aptly-bash-completion/raw/master/aptly -O /etc/bash_completion.d/aptly

### Mac OS X

Bash completion can be installed using [homebrew](http://brew.sh/) completions tap:

  brew tap homebrew/completions
  brew install homebrew/completions/aptly-completion
  
Then load bash completions from your `~/.bashrc`:

    if [ -f `brew --prefix`/etc/bash_completion.d/aptly ]; then
      source `brew --prefix`/etc/bash_completion.d/aptly
    fi

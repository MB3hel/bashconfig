# bashconfig

This repo holds my bash configuration.

## Installation
- Install [Oh My Bash](https://ohmybash.nntoan.com/)
- Clone this repo to `~/.bashconfig`
- Populate `~/.bashrc` with the following

```sh

# Load generic zsh configuration
. ~/.bashconfig/bashrc

# System specific Environment Variables & other settings below

```

- Populate `~/.bash_profile` with the following

```sh
source ~/.bashrc
```
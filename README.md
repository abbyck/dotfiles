# dotfiles
dotfiles for my system

## Requirements

Ensure you have the following installed on your system.
As I'm using Arch Linux as my primary distribution, I'll use pacman to
install the dependencies

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/abbyck/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

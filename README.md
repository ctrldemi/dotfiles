# My dotfiles

Dotfiles for my system

## Requirements

Make sure you have the following installed

### Git

```
sudo pacman -S git
```

### Stow

```
sudo pacman -S stow
```

## Installation

Ckeck out the dotfiles repo in your $HOME directory using git

```
git clone git@github.com:ctrldemi/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks

```
stow .
```
Please refer to this video for further details:
https://www.youtube.com/watch?v=y6XCebnB9gs

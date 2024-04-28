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

Then use GNU stow to create symlinks

```
stow .
```

For directories outside $HOME stow singularly specifying the target
We will use the /etc/ directory as an example

```
stow etc -t /etc/
```

Please refer to this video for further details:
https://www.youtube.com/watch?v=y6XCebnB9gs

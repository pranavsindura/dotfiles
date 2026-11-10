# dotfiles

This is a Linux / MacOS specific project. Steps might not be useful for Windows.

## Adding and Removing Symlinks

[Adding Symlinks](https://www.linode.com/docs/guides/linux-symlinks/)
[Removing Symlinks](https://www.linode.com/docs/guides/linux-remove-symbolic-link/)

## Usage

```bash
# Setup $XDG_CONFIG_HOME in your .zprofile, if it does not already exist
...
export XDG_CONFIG_HOME="$HOME/.config"
mkdir -p "$XDG_CONFIG_HOME"
...
```

```bash
cd $XDG_CONFIG_HOME
ln -s ~/Projects/dotfiles/alacritty alacritty
ln -s ~/Projects/dotfiles/tmux tmux
cd ~
ln -s ~/Projects/dotfiles/.zshrc .zshrc
ln -s ~/Projects/dotfiles/.zprofile .zprofile
ln -s ~/Projects/dotfiles/.gitconfig .gitconfig
ln -s ~/Projects/dotfiles/themes.gitconfig themes.gitconfig
```

## Other Tools

- git
- alacritty
- ohmyzsh
- neovim
- tmux + tpm
- nerd fonts
  - JetBrainsMono Nerd Font Mono
- fzf
- ripgrep
- nvm

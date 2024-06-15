# dotfiles

## Adding and Removing Symlinks

[Adding Symlinks](https://www.linode.com/docs/guides/linux-symlinks/)
[Removing Symlinks](https://www.linode.com/docs/guides/linux-remove-symbolic-link/)

## Usage

```bash
# Setup $XDG_CONFIG_HOME in your .zprofile, if it does not already exist
...
export $XDG_CONFIG_HOME="$HOME/.config"
...
```

```bash
cd $XDG_CONFIG_HOME
ln -s ~/SourceCode/dotfiles/lazygit lazygit
ln -s ~/SourceCode/dotfiles/ranger ranger
ln -s ~/SourceCode/dotfiles/kitty kitty
ln -s ~/SourceCode/dotfiles/alacritty alacritty
ln -s ~/SourceCode/dotfiles/tmux tmux
cd ~
ln -s ~/SourceCode/dotfiles/.gitconfig .gitconfig
ln -s ~/SourceCode/dotfiles/themes.gitconfig themes.gitconfig
```

## Other Tools

- git
- alacritty
- zsh
  - default shell
  - zsh-autosuggestions
- neofetch
- ohmyzsh
- zoxide
- neovim
  - neovim remote - [nvr](https://github.com/mhinz/neovim-remote)
- tmux
  - install tpm as per default installation
- nerd fonts
  - Hack Nerd Font Mono
  - JetBrainsMono Nerd Font Mono
- fzf
- ripgrep
- lazygit
- nvm

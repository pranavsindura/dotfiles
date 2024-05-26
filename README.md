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
- tmux
  - install tpm as per default installation
- nerd fonts
  - Hack Nerd Font Mono
  - JetBrainsMono Nerd Font Mono
- fzf
- ripgrep
- lazygit
- nvm

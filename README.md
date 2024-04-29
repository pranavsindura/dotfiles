# dotfiles

## Adding and Removing Symlinks

[Adding Symlinks](https://www.linode.com/docs/guides/linux-symlinks/)
[Removing Symlinks](https://www.linode.com/docs/guides/linux-remove-symbolic-link/)

## Usage

```bash
# Make sure $XDG_CONFIG_HOME is set (set to ~/.config on my machine)
cd ~/.config
ln -s ~/SourceCode/dotfiles/lazygit lazygit
ln -s ~/SourceCode/dotfiles/ranger ranger
ln -s ~/SourceCode/dotfiles/kitty kitty
ln -s ~/SourceCode/dotfiles/alacritty alacritty
ln -s ~/SourceCode/dotfiles/tmux tmux
```

# dotfiles

My personal config files.

## Alacritty

`alacritty/alacritty.toml`: One Dark Pro theme, FiraCode Nerd Font, PowerShell 7.

Setup on a new machine: clone this repo to `C:\Users\<you>\dotfiles`, then create
`%APPDATA%\alacritty\alacritty.toml` containing:

```toml
[general]
import = ["C:/Users/<you>/dotfiles/alacritty/alacritty.toml"]
```

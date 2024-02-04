# Alacritty Settings

Settings for [Alacritty](https://alacritty.org/), a cross-platform, OpenGL terminal emulator.

## Requirements

- [Alacritty](https://alacritty.org/)
- [UbuntuMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/UbuntuMono#ubuntu-mono)
- [catppuccin theme](https://github.com/catppuccin/alacritty)
- [darkman](https://gitlab.com/WhyNotHugo/darkman)

## Installation

To install, clone the repository to `~/.config/alacritty` and copy `dark-mode.d` and `light-mode.d` to `/usr/local/share/`:

```bash
mkdir ~/.config/alacritty
cd ~/.config/alacritty
git clone https://github.com/joaothallis/config-alacritty.git
sudo cp -r dark-mode.d light-mode.d /usr/local/share/
```

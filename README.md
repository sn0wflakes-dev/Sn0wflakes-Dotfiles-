# Dotfiles

My personal dotfiles for NixOS.

## Managed With
- [GNU Stow](https://www.gnu.org/software/stow/) for symlink management  
- [Home Manager](https://nix-community.github.io/home-manager/) for NixOS integration  

## Structure
Each directory inside this repo represents a configuration for a specific program
Dotfiles/
├── alacritty/
│ └── alacritty.toml
├── waybar/
│ ├── config.jsonc
│ ├── style.css
│ └── waybar.sh
└── hypr/
└── hyprland.conf

## Usage

Clone this repository:

```bash
git clone git@github.com:username/Dotfiles.git ~/Dotfiles
cd ~/Dotfiles 
```

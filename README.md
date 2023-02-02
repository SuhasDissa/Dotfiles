# Dotfiles
My personal dotfiles for hyprland tiling wm

<div align="center">
<img src="https://user-images.githubusercontent.com/64766434/216217781-e16d552a-4de6-49e6-8259-06670ea6e89a.png" width="80%">
</div>
<div align="center">
<img src="https://user-images.githubusercontent.com/64766434/216218373-ae0fe8a9-4679-43da-93a9-23e473de316d.png" width="40%">
<img src="https://user-images.githubusercontent.com/64766434/216219393-53bfda16-d616-4843-8277-7a4f9afd6193.png" width="40%">
</div>

# Get Started
## Required packages

You need to have [Chaoic-Aur](https://aur.chaotic.cx/) configured
```bash
sudo pacman -S hyprland-git waybar-hyprland-git swaybg wlogout rofi wl-clipboard grim slurp kitty brightnessctl pamixer dunst polkit-kde-agent
```

- `swaybg` : Wallpaper support
- `rofi` : App launcher
- `grim` +  `slurp` : Screenshot support
- `kitty` : Terminal
- `dunst` : Notification support
- `wlogout` : Logout screen
- `pamixer` : Audio volume control

## Optional Packages

```bash
sudo pacman -S thunar thunar-archive-plugin thunar-media-tags-plugin thunar-volman gvfs fish
```

- `thunar` : File Manager
- `fish` : Shell (similar to bash but advanced)

## Theme packages (Recommended)

```bash
sudo pacman -S lxappearance materia-gtk-theme papirus-icon-theme
```

Use `lxappearance` to change theme after installing the themes

## Fonts

Install [CascadiaCode](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/CascadiaCode.zip) font to fix missing icons in waybar

# Usage

Open terminal and run following commands (Dont be lazy, type the commands instead of copy paste. otherwise I'm not responsible for any damage you may do to your system)

Install `git` if you dont have it installed

```bash
cd ~/
git clone "https://github.com/SuhasDissa/Dotfiles.git"
cd Dotfiles/
sh create_links.sh
```

After running above commands you will see a **Dotfiles** folder in you home directory ( do not delete it) 
Open the folder in your favourite text editor and edit the files to customize the configs. Changes will be applied automatically.

<!-- vim: set fenc=utf-8 ts=2 sw=0 sts=0 sr et si tw=0 fdm=marker fmr={{{,}}}: -->
# sway-rice
These are the configuration files for all of the programs I am going to use inside Sway, a Wayland compositor.

## Installation
This Git repo contains `dotconfig` and `dotlocal`. These correspond to `~/.config` and `~/.local` respectively. So, you can go two ways about 'installing' these.

Replace `/path/to/clone/folder/` with the folder you want to clone the Git repo inside. Your choice, could be your Home directory.

### Symlinks (you need to keep the cloned folder)
```bash
cd /path/to/clone/folder/
git clone https://github.com/Andy3153/sway-rice/
ln -s /path/to/clone/folder/sway-rice/dotconfig/* ~/.config
ln -s /path/to/clone/folder/sway-rice/dotlocal/* ~/.local
```

### Copying (feel free to delete the folder)
```bash
cd /path/to/clone/folder/
git clone https://github.com/Andy3153/sway-rice/
cd sway-rice/
cp -r dotconfig/* ~/.config
cp -r dotlocal/* ~/.local
cd ..
rm -rf sway-rice/
```

## Dependencies (in Arch Linux package names)
`sway swaybg swayidle swaylock rofi-lbonn-wayland foot sov grim slurp xdg-user-dirs jq wl-clipboard ttf-iosevka-nerd ttf-nerd-fonts-symbols`

## Other dotfiles of mine
- [Zsh config](https://github.com/Andy3153/andy3153-zshrc)
- [Neovim config](https://github.com/Andy3153/andy3153-init.lua)

## Contributing
Feel free to give me advice on this, or even help me with it!

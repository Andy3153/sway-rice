<!-- vim: set fenc=utf-8 ts=2 sw=0 sts=0 sr et si tw=0 fdm=marker fmr={{{,}}}: -->
# sway-rice
These are the configuration files for all of the programs I am going to use inside Sway, a Wayland compositor.

## Dependencies (in Arch Linux package names)
`sway swaybg swayidle swaylock rofi-lbonn-wayland foot sov grim slurp xdg-user-dirs jq wl-clipboard ttf-iosevka-nerd ttf-nerd-fonts-symbols`

## Installation
This Git repo contains `dotconfig` and `dotlocal`. These correspond to `~/.config` and `~/.local` respectively. So, you can go two ways about 'installing' these.

Firstly, clone the repo:
```bash
cd /path/to/clone/folder/
git clone https://github.com/Andy3153/sway-rice/
```

(replace `/path/to/clone/folder/` with the folder you want to clone the Git repo inside. Your choice, could be your Home directory)

Then, follow either of these methods:

- Symlinks (you need to keep the cloned folder)
```bash
ln -s /path/to/clone/folder/sway-rice/dotconfig/* ~/.config
ln -s /path/to/clone/folder/sway-rice/dotlocal/* ~/.local
```

- Copying
```bash
cd sway-rice/
cp -r dotconfig/* ~/.config
cp -r dotlocal/* ~/.local
cd ..
rm -rf sway-rice/ # feel free to delete the folder
```

## The `etc` folder

This folder contains some other stuff I use. See the [README](etc/) inside that folder for more info.

## TODO
- [ ] control volume
- [ ] control brightness
- [ ] swaybar
- [ ] notifications
- [ ] notification popups for some shortcuts
- [ ] separate parts of sway config in files?
- [ ] pywal?

## Other dotfiles of mine
- [Zsh config](https://github.com/Andy3153/andy3153-zshrc)
- [Neovim config](https://github.com/Andy3153/andy3153-init.lua)

## Contributing
Feel free to give me advice on this, or even help me with it!

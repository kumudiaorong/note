# arch linux
## use desktop environment
```bash
sudo pacman -S plasma kde-accessibility kde-graphics kde-system kde-utilities cups ffmpegthumbs 
sudo systemctl enable sddm
```

## configure font
```bash
sudo pacman -S noto-fonts noto-fonts-cjk noto-fonts-emoji
```

## configure input method
```bash
sudo pacman -S fcitx5 fcitx5-chinese-addons  fcitx5-input-support
```

## install software
### install
#### direct install
```bash
sudo pacman -S firefox 
```
#### aur install
install yay
```bash
sudo pacman -S --needed base-devel git
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

install software
```bash
yay -S visual-studio-code-bin
```

#### auto start
system settings -> system -> auto start -> add -> yakuake


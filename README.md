```sudo pacman -S xorg xorg-xinit i3-gaps i3lock i3status i3blocks dmenu kitty firefox```

```sudo cp /etc/X11/xinit/xinitrc ~/.xinitrc```

edit ~/.xinitrc and replace the last 5 lines with ```exec i3```

```startx```

create a new config and set the mod key to "Win"

hit Win+Enter

```sudo pacman -S feh compton```

```git clone https://github.com/7-s3m-7/i3.git```

```sudo cp -r i3/Wallpapers ~/Wallpapers ; sudo cp i3/i3/config ~/.config/i3/config ; sudo cp i3/i3status/i3status.conf ~/.config/i3status/i3status.conf ; sudo cp i3/kitty/kitty.conf ~/.config/kitty/kitty.conf ; sudo cp i3/compton.conf ~/.config/compton.conf```

```sudo rm -rf i3```

hit Win+Shift+R

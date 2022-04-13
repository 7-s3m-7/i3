```sudo pacman -S xorg xorg-xinit i3-gaps i3lock i3status i3blocks dmenu kitty firefox```
```sudo cp /etc/X11/xinit/xinitrc ~/.xinitrc```
edit ~/.xinitrc and replace the last 5 lines with ```exec i3```
```startx```
create a new config and set the mod key to <win>
..

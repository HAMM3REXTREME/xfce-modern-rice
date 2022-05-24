# xfce-modern-rice
Nice and simple Xfce rice.
Tested on Xfce 4.16 on Arch BTW.

![Example Screenshot](https://github.com/HAMM3REXTREME/xfce-modern-rice/raw/master/screenshot-1.png)
![Another Screenshot](https://github.com/HAMM3REXTREME/xfce-modern-rice/raw/master/screenshot-2.png)

# Things used for rice:
- Colloid GTK Theme
- Whisker Menu
- Elementary XFCE Icons
- lightdm-slick-greeter

### Tips:
- It might be useful to install extra packages like `xfce4-goodies`, `pavucontrol`, `lightdm-slick-greeter`, `gvfs`, `catfish`.
- Use `gsettings set org.gnome.desktop.interface color-scheme prefer-dark` to make GTK4 apps prefer dark theme.
- Stuff to download (outside official repos):
    - [lightdm-settings](https://aur.archlinux.org/packages/lightdm-settings)
    - [Colloid GTK Theme](https://github.com/vinceliuice/Colloid-gtk-theme)
    - [Elementary XFCE Icons](https://github.com/shimmerproject/elementary-xfce)

# Installation:
Install the prerequisites (refer to the previous section) and clone this repo.  
Copy files inside `config` folder to `~/.config`.
You can overwrite files of an older/default config.  
**Note:** It is highly recommended to move the files while logged into a tty and not a DE.  

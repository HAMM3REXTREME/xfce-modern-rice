# xfce-modern-rice
Nice and simple Xfce rice.
Tested on Xfce 4.18 on Arch BTW.

![Example Screenshot](https://github.com/HAMM3REXTREME/xfce-modern-rice/raw/master/screenshot-1.png)
![Another Screenshot](https://github.com/HAMM3REXTREME/xfce-modern-rice/raw/master/screenshot-2.png)
*Screenshots might not not be up to date*

# Main things used for rice:
- Colloid GTK Theme *or* adw-gtk3
- Whisker Menu
- Papirus Icon Theme
- lightdm-slick-greeter

### Tips:
- It might be useful to install extra packages like `xfce4-goodies`, `pavucontrol`, `lightdm-slick-greeter`, `gvfs`, `catfish`. Refer to `*.packages`, which are examples of all the packages installed. Don't just blindly install all the packages there though.
- Use `gsettings set org.gnome.desktop.interface color-scheme prefer-dark` to make GTK4 apps prefer dark theme.
- Stuff to download (outside official repos):
    - [lightdm-settings](https://aur.archlinux.org/packages/lightdm-settings)
    - [Colloid GTK Theme](https://github.com/vinceliuice/Colloid-gtk-theme)

# Installation:
Install the prerequisites (refer to the previous section) and clone this repo.  
Copy the content of the `config` folder to your `~/.config`.
You can overwrite SOME files if needed. Review the changes first.  

### Notes:
- Copy the files while logged into a tty and not a DE for the changes to actually take effect.    
- You might want to skip copying some highly specific config files like Keyboard layouts and Monitor config.

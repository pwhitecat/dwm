# Putol's dwm (6.2) 

## !!! Under Development !!!

#### Todo
1. Add autostart patch

## About
dwm is an extremely fast, small, and dynamic window manager for X created by [suckless guys](https://suckless.org/).

## Requirements
- Xlib header files

## Installation
```sh
git clone https://github.com/pwhitecat/dwm ~/.local/share/dwm
cd ~/.local/share/dwm/
sudo make clean install
```

### Running dwm
Below is the `dwm.desktop` that should be located at `/usr/share/xsessions/` for login manager.
```
[Desktop Entry]
Encoding=UTF-8
Name=Dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```

Else add the following these in `.xinitrc` file
```
exec dwm
```

###### END
- Check [suckless website](https://dwm.suckless.org/) for more information about dwm


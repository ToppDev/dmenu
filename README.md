# dmenu - dynamic menu (suckless)

This is my fork of [dmenu, the dynamic menu](https://tools.suckless.org/dmenu/) which is an efficient dynamic menu for X.


## Requirements

In order to build dmenu you need
- the Xlib header files


## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu

```
sudo make clean install
```

## Patches applied

- [allow-color-font](https://tools.suckless.org/dmenu/patches/allow-color-font/)
- [alpha](https://tools.suckless.org/dmenu/patches/alpha/)
- [mouse-support](https://tools.suckless.org/dmenu/patches/mouse-support/)
- [password](https://tools.suckless.org/dmenu/patches/password/)
- [preselect](https://tools.suckless.org/dmenu/patches/preselect/)
- [printindex](https://tools.suckless.org/dmenu/patches/printindex/)
- [reject-no-match](https://tools.suckless.org/dmenu/patches/reject-no-match/)
- [xresources](https://tools.suckless.org/dmenu/patches/xresources/) (modified version by [Luke Smith](https://github.com/LukeSmithxyz/dmenu))
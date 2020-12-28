# dmenu - dynamic menu

*  what is  dmenu? 

dmenu is an efficient dynamic menu for X. made by the the [suckless](suckless.org) guys
it an anti bloat launch application and this is my dmenu costume build


## Requirements
In order to build dmenu you need the Xlib header files.

# Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):
* from arch user repo (aur):
```bash
yay -S dmenu-abdellatif
```

* compile it yourself:
```bash
make clean install
```

## Running dmenu
See the man page for details.

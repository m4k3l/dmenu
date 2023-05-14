# dmenu - dynamic menu
My build of dmenu, an efficient dynamic menu for X.

Forked from [suckless](git.suckless.org)


## Patches
The following patches have been applied:

* [border](https://tools.suckless.org/dmenu/patches/border)
* [center](https://tools.suckless.org/dmenu/patches/center)
* [alpha](https://tools.suckless.org/dmenu/patches/alpha)
* [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch)
* [fuzzyhighlight](https://tools.suckless.org/dmenu/patches/fuzzyhighlight)


## Requirements
In order to build dmenu you need the Xlib header files.


## Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

```
make clean install
```

## Running dmenu
See the man page for details.

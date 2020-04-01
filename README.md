# tabbed - generic tabbed interface Fork

tabbed is a simple tabbed X window container.

## Requirements

In order to build tabbed you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

    make clean install

## Running tabbed

See the man page for details.

## Applied Patches

- [Alpha](https://tools.suckless.org/tabbed/patches/alpha/alpha.diff)
- [Hide tabs](https://tools.suckless.org/tabbed/patches/hidetabs/tabbed-hidetabs-20191216-b5f9ec6.diff)
- [Tabbed Keyrelease](https://tools.suckless.org/tabbed/patches/keyrelease/tabbed-keyrelease-20191216-b5f9ec6.diff)

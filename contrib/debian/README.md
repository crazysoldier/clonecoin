
Debian
====================
This directory contains files used to package clonecoind/clonecoin-qt
for Debian-based Linux systems. If you compile clonecoind/clonecoin-qt yourself, there are some useful files here.

## clonecoin: URI support ##


clonecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install clonecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your clonecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/clonecoin128.png` to `/usr/share/pixmaps`

clonecoin-qt.protocol (KDE)


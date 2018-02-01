
Debian
====================
This directory contains files used to package criptoreald/criptoreal-qt
for Debian-based Linux systems. If you compile criptoreald/criptoreal-qt yourself, there are some useful files here.

## criptoreal: URI support ##


criptoreal-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install criptoreal-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your criptoreal-qt binary to `/usr/bin`
and the `../../share/pixmaps/criptoreal128.png` to `/usr/share/pixmaps`

criptoreal-qt.protocol (KDE)


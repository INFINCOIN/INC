
Debian
====================
This directory contains files used to package infincoind/infincoin-qt
for Debian-based Linux systems. If you compile infincoind/infincoin-qt yourself, there are some useful files here.

## infincoin: URI support ##


infincoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install infincoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your infincoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/infincoin128.png` to `/usr/share/pixmaps`

infincoin-qt.protocol (KDE)


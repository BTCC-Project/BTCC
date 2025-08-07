
Debian
====================
This directory contains files used to package btccd/btcc-qt
for Debian-based Linux systems. If you compile btccd/btcc-qt yourself, there are some useful files here.

## btcc: URI support ##


btcc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install btcc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your btcc-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

btcc-qt.protocol (KDE)


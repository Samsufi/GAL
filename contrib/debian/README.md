
Debian
====================
This directory contains files used to package galrd/galr-qt
for Debian-based Linux systems. If you compile galrd/galr-qt yourself, there are some useful files here.

## galr: URI support ##


galr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install galr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your galrqt binary to `/usr/bin`
and the `../../share/pixmaps/galr128.png` to `/usr/share/pixmaps`

galr-qt.protocol (KDE)


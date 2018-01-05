
Debian
====================
This directory contains files used to package tgisd/tgis-qt
for Debian-based Linux systems. If you compile tgisd/tgis-qt yourself, there are some useful files here.

## tgis: URI support ##


tgis-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tgis-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tgisqt binary to `/usr/bin`
and the `../../share/pixmaps/tgis128.png` to `/usr/share/pixmaps`

tgis-qt.protocol (KDE)



Debian
====================
This directory contains files used to package soorid/soori-qt
for Debian-based Linux systems. If you compile soorid/soori-qt yourself, there are some useful files here.

## soori: URI support ##


soori-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install soori-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your soori-qt binary to `/usr/bin`
and the `../../share/pixmaps/soori128.png` to `/usr/share/pixmaps`

soori-qt.protocol (KDE)


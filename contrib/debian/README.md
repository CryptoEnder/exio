
Debian
====================
This directory contains files used to package exiod/exio-qt
for Debian-based Linux systems. If you compile exiod/exio-qt yourself, there are some useful files here.

## exio: URI support ##


exio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install exio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your exioqt binary to `/usr/bin`
and the `../../share/pixmaps/exio128.png` to `/usr/share/pixmaps`

exio-qt.protocol (KDE)


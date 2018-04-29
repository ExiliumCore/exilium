
Debian
====================
This directory contains files used to package exiliumd/exilium-qt
for Debian-based Linux systems. If you compile exiliumd/exilium-qt yourself, there are some useful files here.

## exilium: URI support ##


exilium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install exilium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your exilium-qt binary to `/usr/bin`
and the `../../share/pixmaps/exilium128.png` to `/usr/share/pixmaps`

exilium-qt.protocol (KDE)


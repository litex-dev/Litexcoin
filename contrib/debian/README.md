
Debian
====================
This directory contains files used to package ltxd/ltx-qt
for Debian-based Linux systems. If you compile ltxd/ltx-qt yourself, there are some useful files here.

## ltx: URI support ##


ltx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ltx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ltxqt binary to `/usr/bin`
and the `../../share/pixmaps/ltx128.png` to `/usr/share/pixmaps`

ltx-qt.protocol (KDE)


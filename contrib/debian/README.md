
Debian
====================
This directory contains files used to package loodd/lood-qt
for Debian-based Linux systems. If you compile loodd/lood-qt yourself, there are some useful files here.

## lood: URI support ##


lood-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lood-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lood-qt binary to `/usr/bin`
and the `../../share/pixmaps/lood128.png` to `/usr/share/pixmaps`

lood-qt.protocol (KDE)


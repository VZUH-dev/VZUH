
Debian
====================
This directory contains files used to package vzuhd/vzuh-qt
for Debian-based Linux systems. If you compile vzuhd/vzuh-qt yourself, there are some useful files here.

## vzuh: URI support ##


vzuh-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vzuh-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vzuhqt binary to `/usr/bin`
and the `../../share/pixmaps/vzuh128.png` to `/usr/share/pixmaps`

vzuh-qt.protocol (KDE)


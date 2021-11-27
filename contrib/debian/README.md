
Debian
====================
This directory contains files used to package COVID19d/COVID19-qt
for Debian-based Linux systems. If you compile COVID19d/COVID19-qt yourself, there are some useful files here.

## COVID19: URI support ##


COVID19-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install COVID19-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your COVID19qt binary to `/usr/bin`
and the `../../share/pixmaps/COVID19128.png` to `/usr/share/pixmaps`

COVID19-qt.protocol (KDE)


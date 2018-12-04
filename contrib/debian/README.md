
Debian
====================
This directory contains files used to package tourcoind/tourcoin-qt
for Debian-based Linux systems. If you compile tourcoind/tourcoin-qt yourself, there are some useful files here.

## tourcoin: URI support ##


tourcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tourcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tourcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/tourcoin128.png` to `/usr/share/pixmaps`

tourcoin-qt.protocol (KDE)


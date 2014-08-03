
Debian
====================
This directory contains files used to package JMAGcoind/JMAGcoin-qt
for Debian-based Linux systems. If you compile JMAGcoind/JMAGcoin-qt yourself, there are some useful files here.

## JMAGcoin: URI support ##


JMAGcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install JMAGcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your JMAGcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/JMAGcoin128.png` to `/usr/share/pixmaps`

JMAGcoin-qt.protocol (KDE)


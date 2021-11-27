
Debian
====================
This directory contains files used to package hostxcoind/hostxcoin-qt
for Debian-based Linux systems. If you compile hostxcoind/hostxcoin-qt yourself, there are some useful files here.

## hostxcoin: URI support ##


hostxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hostxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hostxcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/hostxcoin128.png` to `/usr/share/pixmaps`

hostxcoin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package spiffcoind/spiffcoin-qt
for Debian-based Linux systems. If you compile spiffcoind/spiffcoin-qt yourself, there are some useful files here.

## spiffcoin: URI support ##


spiffcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install spiffcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your spiffcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

spiffcoin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package hyperdashcoind/hyperdashcoin-qt
for Debian-based Linux systems. If you compile hyperdashcoind/hyperdashcoin-qt yourself, there are some useful files here.

## hyperdashcoin: URI support ##


hyperdashcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hyperdashcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hyperdashcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/hyperdashcoin128.png` to `/usr/share/pixmaps`

hyperdashcoin-qt.protocol (KDE)


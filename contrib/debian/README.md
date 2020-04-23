
Debian
====================
This directory contains files used to package pawcoind/pawcoin-qt
for Debian-based Linux systems. If you compile pawcoind/pawcoin-qt yourself, there are some useful files here.

## pawcoin: URI support ##


pawcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pawcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pawcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/pawcoin128.png` to `/usr/share/pixmaps`

pawcoin-qt.protocol (KDE)


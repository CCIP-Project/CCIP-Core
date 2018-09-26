
Debian
====================
This directory contains files used to package ccipd/ccip-qt
for Debian-based Linux systems. If you compile ccipd/ccip-qt yourself, there are some useful files here.

## ccip: URI support ##


ccip-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ccip-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ccipqt binary to `/usr/bin`
and the `../../share/pixmaps/ccip128.png` to `/usr/share/pixmaps`

ccip-qt.protocol (KDE)



Debian
====================
This directory contains files used to package BRSKd/BRSK-qt
for Debian-based Linux systems. If you compile BRSKd/BRSK-qt yourself, there are some useful files here.

## BRSK: URI support ##


BRSK-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BRSK-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BRSKqt binary to `/usr/bin`
and the `../../share/pixmaps/BRSK128.png` to `/usr/share/pixmaps`

BRSK-qt.protocol (KDE)



Debian
====================
This directory contains files used to package pingvincoind/pingvincoin-qt
for Debian-based Linux systems. If you compile pingvincoind/pingvincoin-qt yourself, there are some useful files here.

## pingvincoin: URI support ##


pingvincoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pingvincoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pingvincoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/pingvincoin128.png` to `/usr/share/pixmaps`

pingvincoin-qt.protocol (KDE)


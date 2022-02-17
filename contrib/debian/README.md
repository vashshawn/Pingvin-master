
Debian
====================
This directory contains files used to package pingvind/pingvin-qt
for Debian-based Linux systems. If you compile pingvind/pingvin-qt yourself, there are some useful files here.

## pingvin: URI support ##


pingvin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pingvin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pingvin-qt binary to `/usr/bin`
and the `../../share/pixmaps/pingvin128.png` to `/usr/share/pixmaps`

pingvin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package eurodollard/eurodollar-qt
for Debian-based Linux systems. If you compile eurodollard/eurodollar-qt yourself, there are some useful files here.

## eurodollar: URI support ##


eurodollar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eurodollar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eurodollar-qt binary to `/usr/bin`
and the `../../share/pixmaps/eurodollar128.png` to `/usr/share/pixmaps`

eurodollar-qt.protocol (KDE)


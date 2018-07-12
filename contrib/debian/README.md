
Debian
====================
This directory contains files used to package dividendd/dividend-qt
for Debian-based Linux systems. If you compile dividendd/dividend-qt yourself, there are some useful files here.

## dividend: URI support ##


dividend-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dividend-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dividendqt binary to `/usr/bin`
and the `../../share/pixmaps/dividend128.png` to `/usr/share/pixmaps`

dividend-qt.protocol (KDE)


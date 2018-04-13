
Debian
====================
This directory contains files used to package lpad/lpa-qt
for Debian-based Linux systems. If you compile lpad/lpa-qt yourself, there are some useful files here.

## lpa: URI support ##


lpa-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lpa-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lpaqt binary to `/usr/bin`
and the `../../share/pixmaps/lpa128.png` to `/usr/share/pixmaps`

lpa-qt.protocol (KDE)


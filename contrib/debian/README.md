
Debian
====================
This directory contains files used to package blowsbigd/blowsbig-qt
for Debian-based Linux systems. If you compile blowsbigd/blowsbig-qt yourself, there are some useful files here.

## blowsbig: URI support ##


blowsbig-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blowsbig-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blowsbigqt binary to `/usr/bin`
and the `../../share/pixmaps/blowsbig128.png` to `/usr/share/pixmaps`

blowsbig-qt.protocol (KDE)



Debian
====================
This directory contains files used to package sascoind/sascoin-qt
for Debian-based Linux systems. If you compile sascoind/sascoin-qt yourself, there are some useful files here.

## sascoin: URI support ##


sascoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sascoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sascoinqt binary to `/usr/bin`
and the `../../share/pixmaps/sascoin128.png` to `/usr/share/pixmaps`

sascoin-qt.protocol (KDE)


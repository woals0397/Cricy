
Debian
====================
This directory contains files used to package cricyd/cricy-qt
for Debian-based Linux systems. If you compile cricyd/cricy-qt yourself, there are some useful files here.

## cricy: URI support ##


cricy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cricy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cricy-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

cricy-qt.protocol (KDE)


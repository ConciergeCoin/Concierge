
Debian
====================
This directory contains files used to package concierged/concierge-qt
for Debian-based Linux systems. If you compile concierged/concierge-qt yourself, there are some useful files here.

## concierge: URI support ##


concierge-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install concierge-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your conciergeqt binary to `/usr/bin`
and the `../../share/pixmaps/concierge128.png` to `/usr/share/pixmaps`

concierge-qt.protocol (KDE)


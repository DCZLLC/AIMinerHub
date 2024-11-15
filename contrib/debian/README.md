
Debian
====================
This directory contains files used to package aiminerhubd/aiminerhub-qt
for Debian-based Linux systems. If you compile aiminerhubd/aiminerhub-qt yourself, there are some useful files here.

## pivx: URI support ##


aiminerhub-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aiminerhub-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aiminerhub-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

aiminerhub-qt.protocol (KDE)


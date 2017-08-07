
Debian
====================
This directory contains files used to package gravitycoind/gravitycoin-qt
for Debian-based Linux systems. If you compile gravitycoind/gravitycoin-qt yourself, there are some useful files here.

## bitcoin: URI support ##


gravitycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gravitycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gravitycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

gravitycoin-qt.protocol (KDE)


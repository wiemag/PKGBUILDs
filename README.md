Arch Linux PKGBUILDs
--------------------

Installation PKGBUILDs for Arch Linux:

- PKGBUILD.arch-headless (currently also on AUR)
- PKGBUILD.sm-c
- PKGBUILD.ssh-email-connector
- PKGBUILD.boot-notif
- PKGBUILD.vidcutmerger


USAGE

Download a chosen PKGBUILD and remove its extension. Put the PKBUILD in a separate directory and run

	$ makepkg -s

or alternatively (without removing the extension)

	$ makepkg -p PKGBUILD.<EXT>

as a normal user and then

	# pacman -U the-created-installation-package.xz

as the root to install the software.

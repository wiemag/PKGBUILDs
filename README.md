Arch Linux PKGBUILDs
--------------------

Installation PKGBUILDs for Arch Linux:

- PKGBUILD.sm-c:	for sendmail-connector
- PKGBUILD.vcm:		for vidcutmerger
- PKGBUILD.s-e-c:	for ssh-email-connect


USAGE

Download a chosen PKGBUILD and remove its extension. Put the PKBUILD in a separate directory and run 

	$ makepkg -s

as a normal user and then

	# pacman -U the-created-installation-package.xz

as the root to install the software.

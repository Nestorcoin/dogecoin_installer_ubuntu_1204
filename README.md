dogecoin_installer_ubuntu_1204
=============================

This is a bash script for obtaining dependencies, downloading, and installing from source
dogecoind and dogecoin-qt (dogecoin core) on Ubuntu 12.04 ONLY. May or may not work on any
other platform. This script has been tested with dogecoin core version 1.7

Use -u flag to compile without UPNP support. To specify QT version use -q flag and vesion
number (only QT4 and QT5 is supported). Default QT version is 4. Dogecoin folder will be
created on the folder where this script is run from.

based on instruction :  https://github.com/dogecoin/dogecoin/blob/master/doc/build-unix.md


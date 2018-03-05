Sparky Backup Desktop

This provides an installation script of varoius desktops, for the Sparky Advanced Installer.

Copyright (C) 2016,2017,2018 Paweł Pijanowski

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
---------------
apt
bash
coreutils
dialog
grep
iputils-ping
rsync
sed
sparky-desktop-data
sparky-backup-core
sparky-xterm
sparky-remsu
wget

Suggests:
-------------
yad

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall

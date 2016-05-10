# plymouth_theme_greenworld
## Greenworld

*Greenworld for Plymouth, the boot splash tool for Linux. It's designed for Arch Linux, but can be used in any installation that uses Plymouth.

https://www.dropbox.com/s/09iv5t6sslirqid/plymoth%20theme%20example.png?dl=0

## How to install the theme
Use your favorite way to install packages from the AUR. For example:

    yaourt -S plymouth

Extract greenworld on /usr/share/plymouth/themes/ with root previleges.

Once extracted you can set it as your theme:

    sudo plymouth-set-default-theme -R greenworld

## How to uninstall the theme
Simply remove the package with pacman:

    sudo pacman -Rs plymouth-theme-greenworld

## License

Copyright (C) 2016 Gugs Monteiro

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

## memcleaner is free software: you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation, either version 3 of the License, or
## (at your option) any later version.
## 
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with this program.  If not, see <http://www.gnu.org/licenses/>
## Name: memcleaner
## Version: 0.2
## License: GPLv3
## Author: davenull - dave-null@riseup.net
## Website: https://www.freenixsecurity.net
## Creation Date: 2014-11-09
## Last Update: 2017-11-11
## Copyright 2014-2017 davenull
## Description: This tool cleans RAM from pagecache, dentries and unused inodes.
## This tool runs from version 2.6.16 on the Linux kernel
## drop_caches does not exist in earlier versions of that kernel.
## This is the means of drop_caches's values
## 1: it cleans pagecache
## 2: it cleans dentries and inodes
## 3: it cleans pagecache, dentries and inodes


To install memcleaner, type these commands:
$ git clone https://github.com/FreeNIX-Security-Labs/memcleaner/
$ cd memcleaner
$ chmod 755 install.sh
# ./install.sh

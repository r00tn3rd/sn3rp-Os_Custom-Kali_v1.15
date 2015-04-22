#  README
#  
#  Copyright 2015 root <root@sn3rp-os>
#  
#  This program is free software; you can redistribute it and/or modify
#  it under the terms of the GNU General Public License as published by
#  the Free Software Foundation; either version 2 of the License, or
#  (at your option) any later version.
#  
#  This program is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  GNU General Public License for more details.
#  
#  You should have received a copy of the GNU General Public License
#  along with this program; if not, write to the Free Software
#  Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
#  MA 02110-1301, USA.
#  
#  
#  This program is free software; you can redistribute it and/or 
#  modify it under the terms of the GNU General Public License as 
#  published by the Free Software Foundation; either version 2 of the 
#  License, or (at your option) any later version. This program is 
#  distributed in the hope that it will be useful, but WITHOUT ANY 
#  WARRANTY; without even the implied warranty of MERCHANTABILITY or 
#  FITNESS FOR A PARTICULAR PURPOSE.  
#  See the GNU General Public License for more details.
#  You should have received a copy of the GNU General Public License
#  along with this program; if not, write to the Free Software
#  Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
#  MA 02110-1301, USA.
#
# README FILE
#__________.__      ___________    .__.__    _________             
#\__    ___|__| ____\_   _________ |__|  |  /   _____/ ____  ____  
#  |    |  |  |/    \|    __)/  _ \|  |  |  \_____  \_/ __ _/ ___\ 
#  |    |  |  |   |  |     \(  <_> |  |  |__/        \  ___\  \___ 
#  |____|  |__|___|  \___  / \____/|__|____/_______  /\___  \___  >
#                  \/    \/                        \/     \/    \/ TM
#
# Presents:
# Sn3rp-Os_Custom-Kali_v.1.15
# Created by: @oo0sn3rp0oo

########################################################################

# INSTALLATION INSTRUCTIONS:

# To install sn3rp-Os you need to run this command in the terminal:

# refractainstaller-gui

# *Special Note:
# Refractainstaller will create and mount a folder named target on
# /target and create it's own swapfile despite what you create in
# gparted,cfdisk,parted etc. The best work around is to simply chroot
# into your root partion while refractainstaller is still creating the
# swap file. eg:

# chroot /target

# Then locate the swapfile in /target/swapfile and delete it.

# Then run this command eg:

# nano /etc/fstab

# Then remove the line that says anything about a swapfile and replace
# it with the following eg:

# /dev/sda5	swap	swap	defaults	0	0
# Now 'ctrl c' in refractainstaller's terminal to stop it and reboot
# all done
# PS: Dnscrypt and Tor both autostart.


#### Special Thanks to;
# n1tr0g3n, Reaperz73, TopHatSec, Anonymous, @An0nKn0wledge, mazdra7,
# riseup.net, autistici.org and of course everyone at Offensive_Security.
# Enjoy!

# yaourt-install
User Friendly Script to install the yaourt tool. It uses the AUR git repos to accomodate the install, and takes care of dependencies.

To use this script perform the following commands: 

$ git clone https://github.com/UsrCletus/yaourt-install.git (If you do not have git do pacman -S git)
$ cd yaourt-install
$ chmod +x yaourt-install
$ ./yaourt-install

NOTE: This script requires that you are part of the wheel group, and you are in that the wheel group is enabled in the /etc/sudoers file. If you are unsure how to perform these actions, please go to: https://wiki.archlinux.org/index.php/Sudo for a full tutorial, or use the forums for assistance.

# yaourt-install
User Friendly Script to install the yaourt tool. It uses the AUR git repos to accomodate the install, and takes care of dependencies.

To download and run this script issue the following commands: 

$ git clone https://github.com/usrcletus/yaourt-install

$ cd yaourt-install

$ ./yaourt-install

Advanced: 
At the end of this script you will be asked if you would like to remove the build directories. If you choose no, you won't have to recompile the yaourt and package-query packages if you require a reinstall, as long as you choose the same install directory during the install process.

You can use this script to upgrade the package-query and yaourt packages by either removing the original build directories or choosing a new directory.

NOTE: This script requires that you are part of the wheel group, and that the wheel group is enabled in the /etc/sudoers file. If you are unsure how to perform these actions, please go to: https://wiki.archlinux.org/index.php/Sudo for a full tutorial, or use the forums for assistance.



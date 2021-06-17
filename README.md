# Simple Wine Helper (SWH)

 Command-line interface wrapper for wine. Write with bash script. Works on linux.
 
 Simple means that it is implemented with short bash script. Users should have basic knowledge of bash and wine.

 **Feature**
* Manage multiple wine binary releases
* Manage multiple wineprefix directories
* Work with distro package manager if it will install winehq to /opt
* Use with winehq repository binary package or your own build
* Support [DXVK](https://github.com/doitsujin/dxvk) binary release package 0.5x-1.9
* Support Kron4ek's [FAudio MinGW (dlls) builds for Wine](https://github.com/Kron4ek/FAudio-Builds) binary release package
* Added "Clean the Open With List" function
* Work with [winetricks](https://wiki.winehq.org/Winetricks)
* Fedora: Download and extract wine-6.8 and wine-6.10 rpms.

 **Thanks**
 * koalaman's [ShellCheck](https://github.com/koalaman/shellcheck) , this tool helps me check bash script for error.

 **3.0.0 Release Notes**
* (1) Separated settings from the main swh file.
* (2) Separated launch function from the main swh file.
* (3) SWH 3 no longer needs to be installed, swh 3 launchers just use `source ./swh/swh3 "$@"`

 **3.0.0 Update Guide**
* (1) Please remove old 1.x or 2.x version swh.
* (2) Please remake launchers for swh 3, use example_launcher3 as temple.

 **Usage**
* Make a dir for swh launchers.
* Download swh: Click "Code button"  -> "Download ZIP".
* Extract ZIP in launcher dir, this dir should contain file "example_launcher3" and "swh" dir.
* In this dir, make every file executable recursively: chmod -R u+x (I have to use "create new file" method to update my files after github commit failed many times.)
* run `example_launcher3 --help` and follow the quick guide.

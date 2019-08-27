# Simple Wine Helper (SWH)

 Command-line interface wrapper for wine. Write with bash script. Works on linux.
 
 Simple means that it is implemented with short bash script, users should have some knowledge of bash.

 **Feature**
* Manage multiple wine binary releases
* Manage multiple wineprefix directories
* Work with distro package manager if it will install winehq to /opt
* Use with winehq repository binary package or your own build
* Support [DXVK](https://github.com/doitsujin/dxvk) binary release package 0.5x-1.0
* Support Kron4ek's [FAudio MinGW (dlls) builds for Wine](https://github.com/Kron4ek/FAudio-Builds) binary release package
* Added "Clean the Open With List" function
* Work with [winetricks](https://wiki.winehq.org/Winetricks)

 **Thanks**
 * koalaman's [ShellCheck](https://github.com/koalaman/shellcheck) , this tool helps me check bash script for error.

 **2.9.0 Update Notes**
* (1) Code cleanup
* (2) Fix wine package download function
* (3) Move global settings to `swh_profile`, you should modify this file. Run `example_launcher c` to generate it.
* (4) Experimental functions removed
* (5) Some commands changed, see `example_app_launcher --help`

 **Usage**
* Install swh to $HOME/bin
* Install winetricks to $HOME/bin
* You may have to add these lines to your .bashrc file:
```
PATH=$PATH:$HOME/bin
export PATH
```
* execute `example_app_launcher --help` and follow the quick guide

# Simple Wine Helper (SWH)

 Command-line interface wrapper for wine. Write with shell script.

 **Feature**
* Manage multiple wine binary releases
* Manage multiple wineprefix directories
* Work with distro (now only Fedora) package manager (dnf)
* Use with winehq repository binary package or your own build
* Work with [DXVK](https://github.com/doitsujin/dxvk) binary release setup script
* Work with [winetricks](https://wiki.winehq.org/Winetricks), the following functions use winetricks verb feature:
* Install d3dcompiler_42
* Install FULL XACT override
* Extract dotnet40 files
* Extract dotnet472 files

 **Change**
* 2.2.0:
* Extract dotnet40 files, using winetricks verb feature
* Extract dotnet472 files, using winetricks verb feature

 **Usage**
 
* Install swh to $HOME/bin
* Install winetricks to $HOME/bin
* You may have to add these lines to your .bashrc file:
```
PATH=$PATH:$HOME/bin
export PATH
```
* execute `example_app_launcher --help` and follow the quick guide

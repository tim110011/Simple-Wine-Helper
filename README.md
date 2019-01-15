# Simple Wine Helper (SWH)

 Command-line interface wrapper for wine. Write with bash script.

 **Feature**
* Manage multiple wine binary releases
* Manage multiple wineprefix directories
* Work with distro (now only Fedora) package manager (dnf)
* Use with winehq repository binary package or your own build
* Work with [DXVK](https://github.com/doitsujin/dxvk) binary release setup script
* Work with [winetricks](https://wiki.winehq.org/Winetricks), the following functions use winetricks verb feature:
* Install d3dcompiler_42
* Install FULL XACT override

 **2.5.0 Upgrade Notes**
* (1) Old launchers not supported. Please remake all old launchers. (I suggest use meld to compare two files)
* (2) Default storage dir changed, see swh_config() in swh. Re-config or move existing $cellar and $table dir.
* (3) finish setp 1 and 2, then your old prefixes will still work.
* (4) Please execute `example_app_launcher --help` to see detailed guide

 **Extra Notes**
* That experimental dotnet extract function will not work with recent wine versions ( wine-3.20 )

 **Usage**
* Install swh to $HOME/bin
* Install winetricks to $HOME/bin
* You may have to add these lines to your .bashrc file:
```
PATH=$PATH:$HOME/bin
export PATH
```
* execute `example_app_launcher --help` and follow the quick guide

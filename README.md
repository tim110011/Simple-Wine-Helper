# Simple Wine Helper (SWH)

 Command-line interface wrapper for wine

 **Feature**
* Manage multiple wine binary releases
* Manage multiple wineprefix directories
* Work with distro (now only Fedora) package manager (dnf)
* Use with winehq repository binary package or your own build
* Work with [winetricks](https://wiki.winehq.org/Winetricks)
* Use winetricks install d3dcompiler_42
* Use winetricks install dotnet40slim from repacks.net
* Use winetricks install dotnet472slim from repacks.net 
* Use winetricks install FULL XACT override
* Work with [DXVK](https://github.com/doitsujin/dxvk) binary release setup script
* Write with shell script

 **Notice**
* You need to manually download these repacks from repacks.net. SWH will tell you their storage path.
* Install dotnet472slim is not supported by winehq, if you're lucky, your game may work.
* When you install dotnet472slim, SWH will not remind you to install dotnet40slim.

 **Usage**
 
* Install swh to $HOME/bin
* Install winetricks to $HOME/bin
* You may have to add these lines to your .bashrc file:
```
PATH=$PATH:$HOME/bin
export PATH
```
* execute `example_app_launcher --help` and follow the quick guide

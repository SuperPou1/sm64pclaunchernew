Here will be the reborn version of my launcher.
# sm64pclauncher
A launcher for super mario 64 pc port. works on linux apt/pacman based distros and Windows.
![screenshot](https://cdn.discordapp.com/attachments/886701656488697878/919333674229583923/Zrzut_ekranu_z_2021-12-11_22-02-23.png)
## Linux installation
1.download latest release and unpack it  
2.run these commands in terminal:  
`cd /directory/to/your/downloaded/launcher` (replace "/directory/to/your/downloaded/launcher" with your directory to the launcher)  
`chmod +x installdepends.sh`  
`chmod +x launcher.py`    
`./installdepends.sh`  
## Windows installation
install [python 3](https://www.python.org/downloads/) and [msys2](https://www.msys2.org/), then download the latest release and unpack it, then doubleclick on `installdepends.bat`.
## Usage
### Running on Windows
doubleclick  on `launcher.py`
### Running on Linux
type in terminal `python3 launcher.py` (you must be in launcher directory)  
or  
doubleclick  on `launcher.py` (this way may not work)
### Using it
To build sm64, press "Build"  
To play, select existing build and click "Play"  
## How to build
Not made yet for new launcher
### Tip
if you want a shortcut to the laucher, on ubuntu, you can do this by making a file called `sm64launcher.desktop` in `/home/username/.local/share/applications/` containing the following:  
`[Desktop Entry]`  
`Name=SM64 launcher`  
`Type=Application`  
`Exec=bash -c "cd path/into/sm64pclauncher ; ./launcher.py"`  
`Icon=/whatever/icon/you/like`  
`Categories=Game;`  
(it may not work on other distros, but it is worth trying!)  
on windows right click the file launcher.py and select create shortcut and move it to desktop, and change the icon it you want

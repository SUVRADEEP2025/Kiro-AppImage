<h2 align="center">KIro  AppImage</h2>
<p align="center">Unofficial / Community provided Visual Studio Code AppImage - stable release</p>

## Get Started

#### [Download the latest stable release](https://github.com/pratyay360/Kiro-AppImage/releases/latest)
- stable release only
- supports update of the AppImage

### Executing
#### File Manager

Double-click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some cases you 
> need mark file as executable. You can do this using File manager -> right click > Properties > Allow Execution,
> or by terminal issuing command `chmod +x VSCode-*.AppImage`

##  better use gear leaver

#### AppImageLauncher
Use AppImageLauncher for better desktop integration ==> [download AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher)

#### Terminal
```bash
chmod +x VSCode-*.AppImage
./VSCode-*.AppImage
```

#### Official source code
The official source code of the Visual Studio Code is available at links provided
https://github.com/microsoft/vscode

#### Build
The AppImage is built from .tar.gz Visual Studio Code package by GitHub Continuous Integration using this
bash script https://github.com/valicm/appimage-bash.

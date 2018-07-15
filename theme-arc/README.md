# The Official OSX-Arc Collection

* **Site:** <br>
Theme: https://www.gnome-look.org/p/1167049/ <br>
Icon: https://www.gnome-look.org/p/1185508/

**Theme Arc-Classic** <br>
GitHub: https://github.com/horst3180/arc-theme <br>
GitLab: https://gitlab.com/users/LinxGem33/projects

**Arc-Icon** <br>
GitHub: https://github.com/horst3180/arc-icon-theme <br>
GitLab: https://gitlab.com/LinxGem33/Arc-X-Icons

**Arc-Menu *(Gnome3)*** <br>
GitLab: https://gitlab.com/LinxGem33/Arc-Menu

**Firefox-Theme** <br>
GitHub:https://github.com/horst3180/arc-firefox-theme

##

|OSX Arc White|OSX Arc Plus|OSX Arc Darker|OSX Arc Shadow|
|:------:|:-----:|:-----:|:-----:|
|![](https://cn.pling.com/img/4/7/5/0/8c43c7300506520877db93f40e16f68005e8.png)|![](https://github.com/LinxGem33/Arc-Menu/blob/master/screenshots/osxp.png?raw=true)|![](https://cn.pling.com/img/b/c/1/9/2663fe7724cdbe48087bf8ffb61ef33d9270.png)|![](https://cn.pling.com/img/4/e/e/e/7aa33dbf66b684e7ca882318e6b400acd1b5.png)|
|Click image to enlarge|Click image to enlarge|Click image to enlarge|Click image to enlarge|

## 
### Installation

Latest stable & beta releases can be downloaded from [Here](https://github.com/LinxGem33/OSX-Arc-Darker/releases)

##

### Packages

Ubuntu & Debian based distributions can now install the newly created Debian packages for easy installation of the theme collection, also all deb files have checksums MD5,SHA1 and SHA256 for file integrity links are below.

##

### Manual Installation

How To Install:

1. Download

2. Extract to /usr/share/themes
or ~/.themes (create it (in your home folder) if necessary);

3. Change via distribution specific tweak tool.

After the installation is complete you can activate the theme with `gnome-tweak-tool` or a similar program by selecting `OSX-Arc-White`, `OSX-Arc-Darker` or `OSX-Arc-Shadow` as Window/GTK+ theme and `OSX-Arc-White`, `OSX-Arc-Darker` or `OSX-Arc-Shadow` as Gnome Shell/Cinnamon theme.

##

### System Requirements

**Note:** If your distribution doesn't ship separate development packages you just need GTK 3 instead of the `-dev` packages.

For the theme to function properly, install the following
* Gnome Shell, GTK 3.14 - 3.22
* The `gnome-themes-standard` package
* The murrine engine. This has different names depending on your distro.
  * `gtk-engine-murrine` (Arch Linux)
  * `gtk2-engines-murrine` (Debian, Ubuntu, elementary OS)
  * `gtk-murrine-engine` (Fedora)
  * `gtk2-engine-murrine` (openSUSE)
  * `gtk-engines-murrine` (Gentoo)

## 

### Uninstall

If previous versions were installed or existed, remove them first.

Run (As ROOT User)

    sudo rm -rf /usr/share/themes/{OSX-Arc-White,OSX-Arc-Darker,OSX-Arc-Shadow}

Run (As Local User)    
    
    rm -rf ~/.local/share/themes/{OSX-Arc-White,OSX-Arc-Darker,OSX-Arc-Shadow}
    
    rm -rf ~/.themes/{OSX-Arc-White,OSX-Arc-Darker,OSX-Arc-Shadow}

## 

### Extra's

### Arc Firefox theme
A theme for Firefox is available at https://github.com/horst3180/arc-firefox-theme

### Arc icon theme
The Arc icon theme is available at https://github.com/horst3180/arc-icon-theme

### Chrome/Chromium theme
To install the Chrome/Chromium theme go to the Extra folder and drag and drop the arc-theme.crx or arc-dark-theme.crx or arc-darker-theme.crx file into the Chrome/Chromium window. The source of the Chrome themes is located in the source folder "OSX-Arc-White > Extra folder > arc-theme.crx.

### Plank theme
To install the Plank theme, copy the `extra/Arc-Plank` folder to `~/.local/share/plank/themes` or to `/usr/share/plank/themes` for system-wide use.
Now open the Plank preferences window by executing `plank --preferences` from a terminal and select `Arc-Plank` as the theme.

### Arc-Dark for Ubuntu Software Center
The Arc Dark theme for the Ubuntu Software Center by [mervick](https://github.com/mervick) can be installed from [here](https://github.com/mervick/arc-dark-software-center). It solves readability issues with Arc Dark and the Ubuntu Software Center.

## 

### Troubleshooting

If you have Ubuntu with a newer GTK/Gnome version than the one included by default (i.e Ubuntu 14.04 with GTK 3.14 or Ubuntu 15.04 with GTK 3.16, etc.) you have to install the theme manually as described above.
This is also true for other distros with a different GTK/Gnome version than the one included by default

--

If you get artifacts like black or invisible backgrounds under Unity, disable overlay scrollbars with

    gsettings set com.canonical.desktop.interface scrollbar-mode normal


## 

### Bugs

Bugs should be reported [here](https://github.com/LinxGem33/OSX-Arc-Darker/issues) on the Github issues page.

##

### Contributions & Suggestions

Any suggestions for features and contributions to the continuing code development can be made via the issue tracker or code contributions via a pull request.

##

### Thanks

Special thanks go to whom I might have stolen scripts or configs

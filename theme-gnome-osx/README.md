# Theme-Gnome-OSX

* **Site Theme:**
https://www.opendesktop.org/p/1171688/

### How to install:

**First:** Just copy the extracted file to a `'.themes'` folder you make in your home directory. 
Then use Tweak-tool to select the GTK and shell theme.
LOG OUT AND BACK IN for changes to take effect !

**Second:** This theme was set out to use *Myriad Set Pro Semibold* (12pt,scaling factor:1,00) as the interface-font. This font is easy to get. Just google it...

Extracted file to a `'.fonts'` folder you make in your home directory.

**Third:** OSX uses titlebuttons on the left-side:
To put the buttons to the left open a terminal:

**gsettings set org.gnome.desktop.wm.preferences button-layout "close,minimize,maximize:"**

To put the buttons back to the right in case you want to revert:

**gsettings set org.gnome.desktop.wm.preferences button-layout ":minimize,maximize,close"**

In Gnome 3.26 gnome-tweak has a option to change the position of the titlebuttons, so the above steps are not necessary.

### Thanks

Special thanks go to whom I might have stolen scripts or configs
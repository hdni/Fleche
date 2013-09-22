# Flèche
A GNOME 3.8 theme for GNOME Shell, GTK 3, Mutter, GNOME Terminal, and Firefox. [See the preview](http://hdni.github.io/rice/assets/fleche_display.png).

## Installation
### GNOME Shell, GTK 3, Mutter
* Put the entire repository in `/usr/share/themes/`
* You can then use the Tweak Tool to set the themes.
* It is safe to remove the firefox.css and gnome-terminal.xml files from the directory.

### Firefox
* Install the [Stylish](https://addons.mozilla.org/en-US/firefox/addon/stylish/) extension.
* Install the [FXChrome](https://addons.mozilla.org/en-US/firefox/addon/fxchrome/) theme.
* Go to your [Add-ons Manager](about:addons), select the User Styles page and then write a new style.
* Give the style a name and paste the contents of firefox.css.
* This style works well with the [Movable Firefox Button](https://addons.mozilla.org/en-us/firefox/addon/movable-firefox-button/), [Favicon Restorer](https://addons.mozilla.org/en-us/firefox/addon/favicon-restorer/?src=search), and [Hide Tabbar](https://addons.mozilla.org/en-us/firefox/addon/hide-tabbar/?src=ss) extensions.

### GNOME Terminal
* Download the [gnome-terminal.xml](https://github.com/hdni/dotfiles/blob/master/gnome-terminal.xml) file and run the following command: `gconftool-2 --load gnome-terminal.xml`. Keep in mind that this will **erase your previous settings**.
* Set the profile to "fleche" by right-clicking on your terminal window and choosing it from the Profiles menu.

## Notes
* This theme is not complete yet, and still has bugs. If you find any, please use the issues tracker!
* A very slightly modified version of Adwaita is included as GTK 2 theme, to avoid the default fallback. A GTK 2 theme will be made... eventually.
* The GNOME Shell theme uses Helvetica Neue. If you do not have it installed, it will use Arimo as fallback; you can get the font [here](https://www.google.com/fonts/download?kit=32ci3aiii8TFh9L2O_kK1w). You can also change the font to your liking in the `gnome-shell.css` file.
* The GNOME Terminal theme includes several profiles, from which you can choose in the Profile settings.

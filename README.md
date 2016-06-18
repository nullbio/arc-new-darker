# Arc New Darker

This is a fork of the Arc Darker theme at https://github.com/horst3180/arc-theme, but optimized for *ONLY* Ubuntu 16.04 Xenial and Unity.

The terminal scrollbar was broken in the official arc-darker version, this fixes that in the gtk.css file whilst retaining the other nice theme changes.

# Arc Theme

Arc is a flat theme with transparent elements for GTK 3, GTK 2 and Gnome-Shell which supports GTK 3 and GTK 2 based desktop environments like Gnome, Unity, Budgie, Pantheon, XFCE, Mate, etc.

#####Arc-Darker

![A full-size screenshot of this theme](http://i.imgur.com/43l2MeY.png)

### Requirements

* Gnome/GTK 3.14, 3.16, 3.18 or 3.20
* `git` so you can clone the repo:
    sudo apt-get install git
* The `gnome-themes-standard` and `gtk2-engines-murrine` packages:
    sudo apt-get install gnome-themes-standard gtk2-engines-murrine

Derivatives of these distributions should work, as well.

### Installation

**Important:** Remove all older versions of the theme from your system before you proceed any further.

    sudo rm -rf /usr/share/themes/arc-new-darker
    sudo rm -rf /usr/share/icons/Arc
    sudo rm -rf /usr/share/icons/Paper

Run the following to install the theme, including icon set:

    git clone https://github.com/nullbio/arc-new-darker.git
    cd arc-new-darker
    sudo cp -R ./arc-new-darker/ /usr/share/themes/
    sudo cp -R ./Paper/ /usr/share/icons/
    sudo cp -R ./Arc/ /usr/share/icons/

After the installation is complete you can activate the theme with `unity-tweak-tool`. The icon set is called `Arc`, the theme is called `arc-new-darker`.

### Extras

#### Arc Firefox theme
Theme from: https://github.com/horst3180/arc-firefox-theme
To install this theme, drag and drop the .xpi file in the Firefox directory into Firefox.

#### Chrome/Chromium theme
Theme from: https://github.com/horst3180/arc-theme
To install this theme, drag and drop the .crx file in the Chrome directory into Chrome.

#### Arc icon set theme (Paper icon set backup)
Theme from: https://github.com/horst3180/arc-icon-theme -- Modified to inherit Paper icon set for missing icons, instead of Moka: https://github.com/snwh/paper-gtk-theme

TextMate 2.0 Alpha Installer
============================

Automatically installs and configures TextMate 2.0 Alpha with ZenHTML, CoffeeScript, Git, RSpec, Cucumber, and the RailsCast Theme.

Notes
-----

# ** This will not overwrite your TextMate 1 installation.

# ** TextMate 1 and TextMate 2 can not run simultaneously. You must close TextMate 1 before running
# TextMate 2


Installation
------------

    bash < <(curl -s https://raw.github.com/josephjaber/TextMate-2.0-Alpha-Bundles/master/textmate_alpha_installer)

Done, now just add TextMate 2 to your applications folder.

### Change Default Font

To change your default font, edit the .tm_properties file in your home folder.

    vim ~/.tm_properties

### Install More Bundles

Manually install more bundles by copying them to:

    ~/Library/Application\ Support/TextMate/Managed/Bundles

### Install More Themes

Manually install more themes by copying them to:

    ~/Library/Application\ Support/TextMate/Managed/Bundles/Themes.tmbundle/Themes/
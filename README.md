# mac-config

Steps for configuring a Mac computer.

## System

### Keyboard, Mouse, and Trackpad Customizations

* Keyboard: Maximize repeat rate and minimize repeat delay
* Keyboard: Add Lock Screen shortcut to Touch Bar
* Trackpad: Turn on "Tap to click"
* Mouse: Increase mouse pointer size and tracking speed

## Software

### App Store Installations

* [XCode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)

### Web Installations

#### Web Essentials

* [iTerm2](https://www.iterm2.com/downloads.html)
* [Chrome](https://www.google.com/chrome/browser/desktop/index.html)
* [Skype](https://www.skype.com/en/download-skype/skype-for-computer/)
* [Citrix Receiver](https://www.citrix.com/downloads/citrix-receiver/mac/receiver-for-mac-latest.html)

#### Web Development

* [Visual Studio Code](https://code.visualstudio.com/download)

    To launch Visual Studio Code by typing `code` at the command line (from <https://stackoverflow.com/questions/29963617/how-to-call-vs-code-editor-from-command-line>):

    1. Open VS Code's Command Palette (`F1`) and type "code" to find the `Shell Command: Install 'code' command in PATH` command.
    2. Invoking that command.
    3. Restart the terminal(s).

* [Android Studio](https://developer.android.com/studio/index.html)
* [Android File Transfer](https://www.android.com/filetransfer/)
* [SQL Workbench/J](http://www.sql-workbench.net/downloads.html)
* [Basecamp](https://basecamp.com/via)
* [Postman](https://www.getpostman.com/apps)
* [.NET SDK](https://dot.net)

#### Robert-Specific

* [Wireshark](https://www.wireshark.org/#download)
* [Particle Dev IDE](https://www.particle.io/products/development-tools/particle-desktop-ide)

### Homebrew Installations

#### Homebrew Essentials

* Homebrew

    1. `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

* bash

    From <https://johndjameson.com/blog/updating-your-shell-with-homebrew/>:

    1. `brew install bash`
    2. `sudo -s`
    3. `echo /usr/local/bin/bash >> /etc/shells`
    4. `chsh -s /usr/local/bin/bash`

    Change iTerm2's Default profile to use the new bash instance:

    1. Open **Preferences**
    2. Go to **Profiles** page
    3. Under the **General** tab, change the **Command** radio from **Login shell** to **Command** and supply `/usr/local/bin/bash -il`

    Command aliases:

    1. `alias ll='ls -AFGhlp'`

#### Homebrew Development

* Github Desktop

    1. `brew cask install github`

* Atlassian SourceTree

    1. `brew cask install sourcetree`

* nvm

    1. `brew install nvm`
    2. Update `.bash_profile` by following to the directions provided as output from step #1.

* Python

    1. `brew install python`

* AWS CLI

    1. `brew install awscli`

* Docker

    1. `brew cask install docker`

* Java

    1. `brew cask install java`

* Cocoapods

    1. `brew install cocoapods`

* Postman

    1. `brew cask install postman`

* SoapUI

    1. `brew cask install soapui`

#### Design & Photography

* Inkscape

    1. `brew cask install xquartz`
    2. `brew cask install inkscape`

* ImageMagick

    1. `brew install imagemagick`

# System Preferences
## Dock
* Select Automatically hide and show the Dock
## Security & Privacy
* Select Allow your Apple Watch to Unlock your Mac
* Enable FileVault
* Turn on Firewall
## Keyboard
* Slide Key Repeat all the way to Fast
* Slide Delay Until Repeat all the way to Short
* Select Use all F1, F2, etc. keys as standard function keys
* Deselect Show Input menu in menu bar
## Mouse
* Select Secondary click
* Slide Tracking speed all the way to Fast
* Select Swipe between pages
## Trackpad
* Select Tap to click
* Select App Exposé

# Applications
First install Xcode Command Line Tools
## Xcode Command Line Tools
    $ xcode-select --install

    Select `Install` once prompt opens
Then install Homebrew and Cask
## Home-brew
	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
## Cask
    $ brew tap caskroom/cask
Then proceed to install applications
## Google Chrome
	$ brew cask install google-chrome
## Docker
[Download latest version of Docker for OS X](https://download.docker.com/mac/stable/Docker.dmg)
## Iterm2
	$ brew cask install iterm2
    $ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
[https://github.com/wesbos/Cobalt2-iterm](https://github.com/wesbos/Cobalt2-iterm)
## Microsoft Office
	$ brew cask install microsoft-office
## Postman
    $ brew cask install postman
## Spectacle
	$ brew cask install spectacle
## Spotify
	$ brew cask install spotify
## Visual Studio Code
	$ brew cask install visual-studio-code
### settings.json
```javascript
// Place your settings in this file to overwrite the default settings
{

// Editor

    // Zoom the font of the editor when using mouse wheel and holding Ctrl
    "editor.mouseWheelZoom": true,

// Window

    // Controls how folders are being reopened after a restart. Select 'none' to never reopen a folder, 'one' to reopen the last folder you worked on or 'all' to reopen all folders of your last session.
    "window.reopenFolders": "none",

// Files

    // Configure glob patterns of file paths to exclude from file watching. Changing this setting requires a restart. When you experience Code consuming lots of cpu time on startup, you can exclude large folders to reduce the initial load.
    "files.watcherExclude": {
        "**/.git/objects/**": true,
        "**/node_modules/**": true
    },

// Search

    // Configure glob patterns for excluding files and folders in searches. Inherits all glob patterns from the files.exclude setting.
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true
    },

// Integrated Terminal

    // Controls the font family of the terminal, this defaults to editor.fontFamily's value.
    "terminal.integrated.fontFamily": "Inconsolata for Powerline"
}
```
## Xamarin Studio
[Download latest version of Xcode](https://developer.apple.com/download/)

    $ brew cask install java
    $ brew cask install mono-mdk
    $ brew cask install xamarin-studio
    $ brew cask install xamarin-android
    $ brew cask install xamarin-ios
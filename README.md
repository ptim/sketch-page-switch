# Sketch Page Switch

>A dummy plugin to quickly switch between pages using shortcuts.

This is a fork of the super useful Sketch Page Switch to suit my own preferences, mainly with respect to naming and keyboard shortcuts.

## Installation

As with any Sketch plugin, you can install many ways. In each case, you'll need to restart sketch to use new plugins.

### With Sketch Toolbox...

Arguably the simplest option, this method will keep plugins it installs up to date.

- install and open Sketch Toolbox
- search for 'page switch'
- 

### The old fashioned, zip file method...

- download the repository using the [Download Zip](https://github.com/ptim/sketch-page-switch/archive/master.zip) button to the right.
- grab the folder `sketch-page-switch-master`
- in Sketch 3, select `Plugins > Reveal Plugins Folder...` from the menu bar, and put it in this folder.

### By Cloning the repo...

This way, you can edit the keyboard shortcuts to suit yourself!

    cd ~/Library/Application Support/com.bohemiancoding.sketch3/Plugins
    git clone https://github.com/ptim/sketch-page-switch.git

To edit the shortcuts, change the keys inside comment on the first line of each file within this plugin.  Eg:

    // Switch between pages (cmd l)


## Usage

Switch Page's options are available via the plugin menu `Plugins > Switch Page > …` or with the following shortcuts:

- <kbd>cmd + ]</kbd> - navigate to the next page
- <kbd>cmd + [</kbd> - navigate to the previous page
- <kbd>cmd + \\</kbd> - navigate to a page selected from a drop down list
- <kbd>cmd + shift + n</kbd> - create a new page
- <kbd>cmd + shift + d</kbd> - duplicate the current page

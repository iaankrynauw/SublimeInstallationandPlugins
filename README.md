# Sublime Installation and Plugins
How to install sublime text 3 in Ubuntu and manage plugins for different programming languages.

##Using the Package Manager (apt-get) to install Sublime Text 3

```bash
sudo add-apt-repository ppa:webupd8team/sublime-text-3
sudo apt-get update
sudo apt-get install sublime-text-installer
```

Type `subl` in the terminal to open up Sublime Text 3.

##Installing Package Control for Sublime Text 3

Package Control allows different programming languages to be recognized by Sublime Text.

After opening Sublime Text 3 by using the `subl` in a terminal, open the Sublime Text Console by pressing `Ctrl\`` or the `View>Show Console` menu.

Goto the Package Control webpage `https://packagecontrol.io/installation`and copy the import script under Sublime Text 3 for Package Control installation in to the console of Sublime Text and hit `Enter`.

Note: After every release of Package Control the installation script will change thus always refer to the installation script on the official Package Controll website

#Example Plugin Installation:


##1. RailsBase16 Color Scheme for Sublime Text

A text colour and formatter for Rails.

Install by using Package Control within Sublime Text 3 press `Ctrl+shift+p`, click on `Install Package` and search for `RailsBase16 Color Schemes` once found select it and the repository will be downloaded to your Sublime packages forlder and will be ready to use immediately unless notified otherwise.

##1. Typescript for AngularJS2 Projects

`Ctrl+shift+p`
Choose `Install Packages`.
Search for `TypeScript`.
Install by selecting TypeScript.

##Finding other packages for new langauges

Find other language packages to install at https://packagecontrol.io/ and read this article for packages with extra functionallity for Ruby on Rails See https://mattbrictson.com/sublime-text-3-recommendations#packages for extra functionallity.
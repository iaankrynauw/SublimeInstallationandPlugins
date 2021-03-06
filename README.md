# Sublime Installation and Plugins
How to install sublime text 3 in Ubuntu and various plugins.

##Using the Package Manager (apt-get) to install Sublime Text 3

```bash
sudo add-apt-repository ppa:webupd8team/sublime-text-3
sudo apt-get update
sudo apt-get install sublime-text-installer
```

Type `subl` in the terminal to open up Sublime Text 3.

##Installing Package Control for Sublime Text 3

After opening Sublime Text 3 by using the `subl` in a terminal, open the Sublime Text Console by pressing `Ctrl + ~`.

Goto the Package Control webpage https://packagecontrol.io/installation and copy the import script under Sublime Text 3 for Package Control installation in to the console of Sublime Text and hit `Enter`.

#Plugins:

Note after a plugin is installed sublime may have to be restarted or a file reloaded.

##1. RailsBase16 Color Scheme for Sublime Text

Press `Ctrl+shift+p`

Choose `Install Packages`.

Search for `RailsBase16 Color Schemes`.

Install by selecting `RailsBase16`.

##2. Typescript for AngularJS2 Projects

`Ctrl+shift+p`

Choose `Install Packages`.

Search for `TypeScript`.

Install by selecting TypeScript.

##3. Git Plugin

`Ctrl+shift+p`

Choose `Install Packages`.

Search for `SublimeGit` and `GitGutter`.

Install by selecting SublimeGit and GitGutter.

SublimeGit Usage:

Status, Add, Commit and Push:

1. Press `Ctrl+shift+p` type `status` select `Git: Status`.

2. Press `s` to stage a file for commit.

3. Press `c` to commit changes.

4. Type the commit message in and press `ctrl+w` to close the file.

5. Press `Ctrl+shift+p` type `push` select `Git: Push`.

GitGutter adds `+` signs next to lines of code that have been added since the last commit.

##4. Ruby on Rails Snippets

Offers ruby on rails code completion.

##5. CapRails

Capistrano Deploy.

##6. RSub

Edit files on a server locally in sublime.

Follow this guide for installation on server and in sublime.

https://wrgms.com/editing-files-remotely-via-ssh-on-sublimetext-3/

##7. Emmet

HTML template generation

Example:
html:5```<press tab>```

generates:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>

</body>
</html>
```

ul#nav>li.item$*4>a{Item $}```<press tab>```

generates:

```html
<ul id="nav">
  <li class="item1"><a href="">Item 1</a></li>
  <li class="item2"><a href="">Item 2</a></li>
  <li class="item3"><a href="">Item 3</a></li>
  <li class="item4"><a href="">Item 4</a></li>
</ul>
```


# Sublime Snippets for StackMob JavaScript
This is a [Sublime Text](http://www.sublimetext.com/) package which includes snippets for doing [StackMob](http://www.stackmob.com) JavaScript development.

![StackMob Sublime](https://s3.amazonaws.com/uploads.hipchat.com/11115/139926/m0l6dz4uwyij2es/sublime-stackmob-js.gif)

## Installation ##

### 1. Find Packages Directory

* Mac `cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User`
* Windows: `cd %APPDATA%\Sublime Text 2\Packages\User`
* Linux: `cd ~/.Sublime\ Text\ 2/Packages` or `cd ~/.config/sublime-text-2/Packages`
* Portable: Sublime Text 2/Data/Packages

Can't find your packages? Open sublime and press ``ctrl + ` `` and type `sublime.packages_path()`.

### 2. Download

    $ git clone git@github.com:wyne/sublime-stackmob-js-snippets.git stackmob-js


## Usage

In a javascript file or within a script tag in an html file, type `sm` as the start to one of the triggers below.

<table>
  <tr>
    <th>Trigger</th>
    <th>StackMobMethod</th>
  </tr>
  <tr>
    <td>smc</td>
    <td>StackMob.create()</td>
  </tr>
  <tr>
    <td>smf</td>
    <td>StackMob.fetch()</td>
  </tr>
  <tr>
    <td>smfe</td>
    <td>StackMob.fetchExpanded()</td>
  </tr>
  <tr>
    <td>smn</td>
    <td>var object = new Object({`property`: "`value`"});</td>
  </tr>
  <tr>
    <td>sminit</td>
    <td>StackMob.init()</td>
  </tr>
</table>

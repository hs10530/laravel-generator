## sublime-laravelgenerator

A Sublime Text plugin that allows you to make use of the [Laravel 4
Generators](https://github.com/JeffreyWay/Laravel-4-Generators) directly within Sublime Text.

## Installation

* Install the  Laravel 4 generator commands through Composer.
* Install the ST plugin through Package Control: *Sublime Laravel Generator*
* If you are on Windows or php executable is not in PATH, please specify the path to it in `laravelgenerator.sublime-settings`. To do so, copy `laravelgenerator.sublime-settings` from this
plugin to `<Packages_Directory>/Users/` and make the edits to that file.

## Usage

* Open a Laravel Project
* Open the command palette (Ctrl+Shift+P)
* Execute any of the available Generate commands

*Note*: `artisan` needs to be in the project root.

## Customization

The plugin is quite extensible. Interested users can extend the plugin for more
artisan commands by adding the appropriate entries in
`Default.sublime-commands`.

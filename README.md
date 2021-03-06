# Choose My CSS plugin for MantisBT

Copyright (c) 2020 Association Cocktail, Marc-Antoine TURBET-DELOF

## Description

_ChooseMyCSS_ is a plugin for [MantisBT](http://mantisbt.org) that 
allows the administrator to add some CSS files optional or mandatory for users.

Admin users create and name CSS files.

Some may be taged as mandatory. Then, they are all included for all users.

The others (not tagged as mandatory) can be chosen by stanard users to be applied in addition.

## Change Log

See the [Change log](CHANGELOG.md).

## Installation

### Requirements

The plugin requires [MantisBT 2.24](https://github.com/mantisbt/mantisbt/tree/release-2.24.0) (not tested on earlier releases).

### Setup Instructions

1. Download or clone a copy of the 
   [plugin's code](https://github.com/mantisbt-plugins/ChooseMyCSS).
2. Copy the plugin (the `ChooseMyCSS/` directory) into your Mantis
   installation's `plugins/` directory.
3. While logged in as an administrator, go to *Manage → Manage Plugins*.
4. In the *Available Plugins* list, you'll find the *ChooseMyCSS* plugin;
   click the **Install** link.
5. In the *Installed Plugins* list, click on the **ChooseMyCSS** plugin to configure it.
6. Users can choose an optional CSS file in *My account → Preferences*.

## Configuration

The list of additional CSS files can be defined on the plugin's config page.

Specify, for each file, if it's optional or mandatory.

All CSS files will be used before mandatory one chosen by a user.

If you chose multi mandatory CSS files, they will be added in the order in which they are displayed.

## Screen Shots

In the plugin config page *Manage → Manage Plugins → ChooseMyCSS*

![add CSS file](screenshots/add_file.png "To add new CSS file")

![edit CSS files](screenshots/edit_file.png "To edit existing CSS file")

In user preferences page  *My account → Preferences* or *Manage → Manage Users → _login_ → Account Preferences*

![choose CSS file](screenshots/choose_file.png "Choose CSS file in account preferences")


## Support

If you wish to file a
[bug report](https://github.com/mantisbt-plugins/ChooseMyCSS/issues/new),
or have questions related to use and installation, please use the plugin's
[issues tracker](https://github.com/mantisbt-plugins/ChooseMyCSS/issues)
on GitHub.

All code contributions (bug fixes, new features and enhancements, translations) 
are welcome and highly encouraged, preferably as a
[Pull Request](https://github.com/mantisbt-plugins/ChooseMyCSS/compare).

The latest source code is available on
[GitHub](https://github.com/mantisbt-plugins/ChooseMyCSS).

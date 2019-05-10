# Base Wordpress Installation

## Description

This script installs a basic wordpress installation that I use for new projects.  It assumes that
you have [git](https://git-scm.com/) and the [wordpress cli](https://wp-cli.org/) installed and working on your machine.

## Usage
Download or clone this repo to your machine. Add the path to `base-wp/bin` to your path and run as `base-wp new-site-directory`.

## Directory Structure
Running `base-wp new-site-directory` will create a `new-site-directory` and install wordpress in a `www` subdirectory.  This matches my personal project setup where I will keep scripts and documentation in the project directory outside of the wordpress docroot.

## Plugins installed
The following are installed by default.  Those that are marked are also activated by default.

* classic-editor
* debug-bar
* disable-embeds (activated)
* disable-emojis (activated)
* editor-menu-and-widget-access (activated)
* ga-google-analytics
* redirection
* timber-library (activated)
* tiny-compress-images
* wordpress-seo (activated)
* wp-mail-smtp
* wp-sweep (activated)

## Theme
A base theme is created from the [Timber Starter Theme](https://github.com/timber/starter-theme).  Please see the
[timber documentation](https://www.upstatement.com/timber/) for more information.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/jesseday/base-wp/blob/master/LICENSE) file for details

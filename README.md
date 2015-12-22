# SodaSeti Theme

Dark and light custom UI themes for Sublime Text 2 and Sublime Text 3 based on the origin and pretty awesome [soda-theme](https://github.com/buymeasoda/soda-theme), combined with the icons of the [Seti_ST3 theme](https://github.com/ctf0/Seti_ST3).

So in the end I only combined the [Soda theme](https://github.com/buymeasoda/soda-theme) with the [Seti theme](https://github.com/ctf0/Seti_ST3).
Therefor all credits belong to those guys!

## Installation

SodaSeti theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install SodaSeti Theme via the `Package Control: Install Package` menu item. The SodaSeti Theme package is listed as `Theme - SodaSeti` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/confirm/soda-seti-theme.git "Theme - SodaSeti"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - SodaSeti`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "SodaSeti Light.sublime-theme"` or `"theme": "SodaSeti Dark.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "SodaSeti Light.sublime-theme"
    }

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "SodaSeti Light 3.sublime-theme"` or `"theme": "SodaSeti Dark 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "SodaSeti Light 3.sublime-theme"
    }

## License

Soda and SodaSeti Themes are licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.


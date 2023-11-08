# Breeze dark theme for FontForge

This fork takes a lot of the original, but changes to make it more palatable on KDE.

Be mindful that it's a quick and dirty theme, there are bugs, there are issues, and is provided as is.

Below is the original Readme. In the installation paragraph, replace `dark.theme` with `kde-breeze-dark.theme`.

Also, if the images don't load in the UI, you might want to edit their path.

Finally, it took me a while to find it (even tho it's quite visible), but there is an UI editor integrated, in the File menu (below Preferences).

# Dark Theme For FontForge

A dark theme for [FontForge](http://fontforge.org)

<img src="https://raw.githubusercontent.com/mooniak/mac-fontforge/master/_screenshots/screen_1.png" alt>

## Features

* Color theme inspired by Inkscape's osxmenu theme, which is inspired by Adobe llustrator, Foundry Nuke and other graphics applications with dark grey colour themes
* Icons from Inkscape's osxmenu icons

## Installation

1. Copy all the files in the `dark` folder to FontForge´s `pixmaps` directory. This may be at one of the following locations:

*  `/Applications/FontForge.app/Contents/Resources/opt/local/share/fontforge/pixmaps/` - Mac
*  `C:\Program Files (x86)\FontForgeBuilds\share\fontforge\pixmaps\` - Windows
*  `/usr/share/fontforge/pixmaps/` - UNIX
*  `/usr/local/share/fontforge/pixmaps/` - UNIX

2. Load FontForge and go open the `File > Preferences` dialog, and set the `ResourceFile` preference to the `dark.theme` file in the above pixmaps folder.

## Known Issues

*  Warnings window text visiblity
*  MM Dialog window text areas clipped
*  Lookups editor text visibility (Element > Font Info > Lookups)


## Credits

Started by [Kemie Guaida](http://www.monolinea.com) as mac-fontforge, and modified into Dark Theme by [Pathum Egodawatta](http://mooniak.com)

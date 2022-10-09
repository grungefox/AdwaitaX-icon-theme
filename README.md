# Introduction:
**AdwaitaX (as in AdwaitaX-panded, or AdwaitaX-tended) is very simple yet quiet usefull set of additional desktop icons for GNOME Shell's default icons.**  

This project's goal is to enchance user experience and match many third-party (including proprietary) apps icons with [Adwaita design](https://developer.gnome.org/hig/guidelines/app-icons.html#gnome-app-icon-style) made by GNOME Project, while still maitaning them as close to the original look as possibile.  
**<sub><sup>Unfortunately, for now in many cases it doesn't respects [GNOME Human Interface Guidelines colour pallete](https://developer.gnome.org/hig/reference/palette.html), and instead tries to use colours of original icon (but there is a future plan of adding special HIG version)</sup></sub>**

**This project _won't_ change any native GTK+ program's icons and neither does include them.** (yes, I'm looking at you [Adwaita++](https://github.com/Bonandry/adwaita-plus))

# Requirements:
- original [Adwaita icon theme](https://gitlab.gnome.org/GNOME/adwaita-icon-theme/-/tree/master/Adwaita) installed (recommended for full experience)

# Installation:
### Manual:
1. [Download `main` branch of this repository](https://github.com/grungefox/AdwaitaX-icon-theme/archive/refs/heads/main.zip)
2. Unzip downloaded files
3. Copy or move them to either `~/.local/share/themes` (create if doesn't exist) or `/usr/share/icons/` (the second option is recommended, but root access is requaried)

(installation script in the future)

# Bugs and requesting new icons:
If you want to report an issue or request a new icon just [create new issue](https://github.com/grungefox/AdwaitaX-icon-theme/issues).  

Howewer request will be denied if:
- it's duplicate of another person request
- the program that icon is requested is already GTK based, even if it doesn't match GNOME HIG (e.g. GIMP, BleachBit, Transmission)
- there is not enaugh information about which app is meant to be added (apps like _Camera_ doesn't say too much about it)
- it's game app or game launcher (only exceptions are native game stores and original Minecraft launcher)

If you know something more about your request - like what name of the file of this icon should be (which you could find mostly in `/usr/share/icons/hicolor/` if you have that app installed or `/var/lib/flatpak/app/app_name/current/active/files/share/icons/hicolor/` if it's installed as flatpak) - would be much appreciated.

Also please keep in mind that [**_this project is maintained by only one person_**](https://github.com/grungefox) and not every request or fix can be done, or at least not done on time. And don't expect this project to be the highest quality imaginable - I only started this project as my attempt at better understanding vector graphics.

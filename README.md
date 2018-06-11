# Freeplay Theme for EmulationStation

Changelog
-----------

- June 1, 2018 - Initial Release

License
-----------
Creative Commons CC BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/3.0/

Screenshots
-----------
![System Select Screen](http://i.imgur.com/wIjmpyt.png) ![Detailed Game List](http://i.imgur.com/AJSVHLx.png)

Recommended EmulationStation UI Settings
-----------
* Carousel Transitions: ON
* Transition Style: Instant
* Gamelist View Style: Automatic

Recommended Installation Method
-----------
1) The easiest install method is using the es-themes menu in Retropie 
2) It can also be manually installed/updated using the commands below
3) See the note at the end of this Readme for a third installation method that gives you each of the 12 color variants to choose from in the UI Settings menu of EmulationStation (note that this install method is completely separate from the es-themes menu in Retropie)

NEW INSTALL (Manual Method):
```
sudo git clone --recursive --depth 1 "https://github.com/rxbrad/es-theme-freeplay.git" "/etc/emulationstation/themes/freeplay"
```

UPDATE EXISTING INSTALL (Manual Method):
```
cd "/etc/emulationstation/themes/freeplay"

sudo git pull

sudo git submodule update --init --recursive
```

Changing Theme Color
-----------
![Red](https://i.imgur.com/YLa8c8At.png)![Orange](https://i.imgur.com/TG7M0THt.png)![Gold](https://i.imgur.com/UU3v0qst.png)![Yellow](https://i.imgur.com/fqaclTht.png)![Green](https://i.imgur.com/b5TOhBKt.png)![Blue](https://i.imgur.com/U47t22Gt.png)![Glacier](https://i.imgur.com/OoUmMJnt.png)![Indigo](https://i.imgur.com/EFXJSg8t.png)![Fuchsia](https://i.imgur.com/d9fSqdWt.png)![White](https://i.imgur.com/nY2fYsYt.png)![Platinum](https://i.imgur.com/pQtRBDAt.png)![Black](https://i.imgur.com/65KWrpTt.png)

There are 12 different color variants for this theme.  The color can be changed by editing the color.xml file, and uncommenting the line for the desired color (make sure that only one line is uncommented).

For a Raspberry Pi RetroPie install, the color can be edited with the following command:
```
sudo nano /etc/emulationstation/themes/freeplay/color.xml
```

I've also created a script that can be used to automatically install/update all 12 color variants at once (this is done outside of the ESThemes utility).  Check it out at https://github.com/rxbrad/rxbrad_themeutils

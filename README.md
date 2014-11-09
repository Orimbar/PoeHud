PoeHud
======

### Latest news

<a href=https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=LPFFQZAANHG9W>Please donate to support the project</a>

Source code is no longer avaliable. This was made mainly to prevent develpoment 3rd party products (bots, autoflaskers, etc.) based on data discovered by me during analysis of Path of Exile binaries.

### Requirements
* .NET framerwork v.4 or newer (you already have it on Windows 8+, otherwise here's your dowload link)
* Slim DX ([download link](http://slimdx.org/download.php) - pick version 4.0, for x86 platform) **Do not install x64 version**
* Windows Vista or newer (XP won't work)
* Path of Exile should be running in Windowed or Windowed Fullscreen mode (the pure Fullscreen mode does not let PoeHUD draw anything over the game window)
* Windows Aero transparency effects must be enabled. (If you get a black screen this is the issue)

### Item alert settings
The file config/crafting_bases.txt has the following syntax:
`Name,[Level],[Quality],[Rarity1,[Rarity2,[Rarity3]]]`

Examples of valid declarations:
```
Vaal Regalia,78
Corsair Sword,78,10
Gold Ring,75,,White,Rare
Ironscale Gauntlets,,10,White,Magic
Quicksilver Flask,1,5
Portal Scroll
Iron Ring
```

# Development Log #6 (4/24/23)
This is the sixth development log of NoLexa. This devlog focuses on the base application to help overall stability and core functions.


## What's New

### Automatic Updates
NoLexa can now automatically check for updates and download the latest version from GitHub. Originally, it would only prompt you telling you that there was a new version, and was using pastebin to recieve the string, which was very unreliable and had the potential to flag antiviruses.
I have now updated that method to check using GitHub, which is more reliable, and have completely automated the updating function by downloading the latest version, unzipping and running it, instead of just giving an update warning.

### Shortcut to Desktop
NoLexa now automatically creates a shortcut to the desktop.

### Internal Organization
Organizing a lot of the internal code for NoLexa has continued.

## New Features

### Settings Improvements
Settings now has a more polished interface and actual settings to adjust.
#### Delete Update Cache
With the new auto-update check, there will be a cache located in the NoLexa folder called UpdateCache, you can delete this folder within the app via settings, or you can do it manually.
#### Check for Updates on Start
You can change if you want to always check for updates when you start NoLexa.





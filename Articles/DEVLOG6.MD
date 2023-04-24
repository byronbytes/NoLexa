# Development Log #6 (4/24/23)
This is the sixth development log of NoLexa. This devlog focuses on the base application to help overall stability and core functions.


## What's New

### Automatic Updates
NoLexa can now automatically check for updates and download the latest version from GitHub. Originally, it would only prompt you telling you that there was a new version, and was using pastebin to recieve the string, which was very unreliable and had the potential to flag antiviruses.
I have now updated that method to check using GitHub which is more reliable, and have completely automated the updating function by instantly downloading the latest version, unzipping and running it.

### Shortcut to Desktop
NoLexa now automatically makes a shortcut to the desktop.

### Internal Changes
More changes to the internals of NoLexa. There are now code summaries for classes, better organization, and more.

## New Features

### Settings Improvements
Settings has been improved with a better UI, and now has new things to modify.
#### Delete Update Cache
With the new auto-update check, there will be a cache located in the NoLexa folder called UpdateCache, you can delete this folder within the app via settings, or you can do it manually.

### 



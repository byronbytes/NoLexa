# Development Log #2 (2/1/23)
This is the second development log of NoLexa, a lot of backend changes and features have been completed and are being tested and stabilized. I had recently taken a break from developing NoLexa for other projects and hobbies, but now I'm back on track with development and I should be able to hit the release date on time.


## New Features

### Directory Creation
By default, there will now be a folder in your Documents folder named "NoLexa", this will have 3 subdirectories called "Screencaps", "Backups", and "Logs". Whenever you create a backup, take a picture, or dump system info to text, they will be put in the corresponding folders. Currently, there is no way to change where the folders are created, but there will be an update that adds this soon.

### Remote Screenshot
You are now able to remotely take pictures of your screen from NoLexa, it takes the picture and sends it to the "Screencaps" directory. At the moment it does not delete the copy of the picture on the device while testing, and the "picture count" system only counts up for the current NoLexa session. Both of these will be fixed in the next update.

### Create Backups
You are now able to backup your device settings, apps, software, pictures, etc via NoLexa, and the backup files will be saves in the "Backups" folder. These take up multiple gigabytes of space so make sure you have enough disk space.

### Disable OTA Updates
You are now able to disable OTA updates from within the app. This is currently highly experimental and there is no way to re-enable updaes at the moment, and will be fixed in the next update.

### Auto-Install ADB
From the "Device Selection" menu, you are now able to install ADB to the proper directory if you have administrator privelages. We will work on a fix so all users can install it.

### Battery Spoofer Hotfix
You are now able to reset the battery percentage to normal instead of having to reboot the device to get the percentage back to normal.

### UI Optimizations and Bug Fixes
Fixed some bugs throughout the interface, inconsistancy, and more.

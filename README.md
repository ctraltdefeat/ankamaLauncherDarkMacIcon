# ankamaLauncherDarkMacIcon

Expand Macintosh HD > Applications > right-click on Ankama Launcher, and select **Show Package Contents**. 

### Changing the Application Icon (Optional)
![Application Sample](https://github.com/ctraltdefeat/ankamaLauncherDarkMacIcon/blob/7d922ce5ab07d8ea5d6d4ce40950517e5616b9a4/Application%20Icon%20Sample.png)
- Expand the */Contents/Resources* directory, rename **`Ankama Launcher.icns`** to **`Ankama Launcher.old`**.
- Upload the Dark Version of Ankama Launcher.icns to this directory.

### Changing the MacOS Tray Icon (This is the whole reason I made this. It's distracting to have colorful icons on the tray.)
![Tray Sample](https://github.com/ctraltdefeat/ankamaLauncherDarkMacIcon/blob/d7ee231e4b67da32b7e77c2c6e97921049cb048b/Tray%20Sample.png)

- Expand the */Contents/Resources/static/tray* directory, rename **`icon.png`** and **`icon@2x.png`** to **`icon.old`** and **`icon@2x.old`**.
- Uploade the Dark Versions of **`icon.png`** and **`icon@2x.png`** to this directory.
- Relaunch the Ankama Launcher.

To undo these changes, delete the dark icons and rename the .old filenames to .icns or .png, respectively.

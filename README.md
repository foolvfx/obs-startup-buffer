# Startup Buffer Guide

##  Python Setup
1. Download and install [python](https://www.python.org/downloads/release/python-3120/) if you do not already have it installed
2. Open OBS and open **Tools -> Scripts**
3. Click on **Python Settings**
4. Click **Browse** and locate your python installation (default location is `C:\Users\%userprofile%\AppData\Local\Programs\Python\Python312`)
5. It should now say "Loaded Python Version: 3.12" (or whatever your python version) under the path
6. Download the [script](/start-buffer.py) and add it to the folder opened when you click the **+** on the OBS **Scripts** Tab
7. Add the Script

## OBS Startup Setup
1. Search for OBS on your windows search and right click -> open file location. It should open to a directory with just the shortcut and uninstall shortcut
2. Click `Win+R` or search for **Run** to open the windows run dialog, type `shell:Startup` and run
3. Copy the shortcut from the initial directory to the Startup folder

## Optional Settings
- If you would like for OBS to start minimized navigate to **Settings -> General -> System Tray** and check **Enable** and **Minimize to system tray when started**
- Once OBS is open you can drag the icon from your system tray to display it on the bottom right of your taskbar
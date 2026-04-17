# starwarfare-vita
![2026-01-04-084058](https://github.com/user-attachments/assets/7f19a835-88bf-4fa4-9dda-5bf00551477d)

This is a a port of Star Warfare: Alien Invasion for the PlayStation Vita, playable with the Vita's controls + with trophies.

# How To Install
* Download and install [the Android version of the game on your phone](https://play.google.com/store/apps/details?id=com.ifreyrgames.starwarfare&hl=en)
* In a file manager of your choice, locate the game's OBB file
```
Internal Storage
└── Android/
    └── obb/
        └── com.ifreyrgames.starwarfarehd/
            └── main.26.com.ifreyrgames.starwarfarehd.obb  <-- Target File
```
* Grab the OBB file and transfer it to your PC
* Download the .zip file from this repository's release page and extract it to a new folder
* Open up the OBB file on your PC with your file manager of choice, and locate the "Data" folder
```
main.26.com.ifreyrgames.starwarfarehd.obb
└── assets/
    └── bin/
        └── Data/ <- This folder
            └── ...
```
* Grab the contents of the Data folder and put them in the "starwarfare" folder in the folder you just extracted
```
Newly extracted folder
└── starwarfare/
    └── ... <- Here!
└── patch_files.bat
└── starwarfare.xdelta
└── deterministic_zip.exe
└── xdelta.exe
```
* Run "patch_files.bat" and let it patch the files
* Once its done, notice how there's now a new file: ``data.zip``
* Download the VPK file from this repository's release page
* Install the VPK onto your Vita using VitaShell
* Using VitaShell, extract the contents of ``data.zip`` and move/copy them to ``ux0:app/STWR00001/``
* Launch the app and enjoy!

# Controls
Left Stick - Move

Right Stick - Look

R - Shoot

Start - Pause

D-Pad - Weapon Switching

Use the touchscreen for everything else

# Credits
AJ170 for helping me with the port

Zweronz for the decompile of the game

Freyr Games for the original game

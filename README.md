# starwarfare-vita
![2026-01-04-084058](https://github.com/user-attachments/assets/7f19a835-88bf-4fa4-9dda-5bf00551477d)
This is a a port of Star Warfare: Alien Invasion for the PlayStation Vita, playable with the Vita's controls + with trophies.

# How To Install
* Get a hold of the game's APK file (version 3.01) and extract it into an folder
* In this folder, grab the following file: ``assets/bin/Data/Managed/SymbolMap-ARMv7``
* Download the .xdelta patch from this repository's release page
* Use a xdelta patching tool to patch ``SymbolMap-ARMv7`` with ``patch_psp2.xdelta``
* Extract the final patched file into a new folder (you might have to rename it so that it has an .ZIP extension)
* Download the VPK file from this repository's release page
* Install the VPK onto your Vita using VitaShell
* Using VitaShell, grab the contents from the patched .ZIP file and move/copy them to ``ux0:app/STWR00001``
* Launch the app and enjoy!

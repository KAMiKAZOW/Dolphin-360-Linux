# Dolphin-360-Linux
Dolphin button mappings for Xbox 360 pads under Linux (Windows ini files don’t work because the input stacks return other values)

## Installation
### Dolphin after the evdev migration
The quickest way is to paste the following command squence into your terminal:

    install -d ~/.config/dolphin-emu/Profiles/Wiimote;cd ~/.config/dolphin-emu/Profiles/Wiimote/;wget https://github.com/KAMiKAZOW/Dolphin-360-Linux/archive/master.zip;unzip -j master.zip;rm master.zip

### Ishiiruka
If you happen to use [Ishiiruka-Dolphin](https://github.com/Tinob/Ishiiruka), enter:

    install -d ~/.config/ishiiruka/Profiles/Wiimote;cd ~/.config/ishiiruka/Profiles/Wiimote/;wget https://github.com/KAMiKAZOW/Dolphin-360-Linux/archive/master.zip;unzip -j master.zip;rm master.zip

### Use different Xbox pads
The ini files here are also compatible with other Xbox pads. Change the line

    Device = evdev/0/Microsoft X-Box 360 pad

to whatever the Dolphin input settings say your pad is called, eg. for the second generation Xbox One pad:

    Device = evdev/0/Microsoft X-Box One S pad

Classic Controller.ini
----------------------
* Mimics **Wii Classic Controller**

DKC + Mario Bros.ini
--------------------
* **Donkey Kong Country Returns** + **New Super Mario Bros. Wii**
* Movement: Left stick
* X and A buttons for Run and Jump
* RB for Roll/Blow/Attack/…
* LT / RT tilt remote sideways (NSMB only)
* LB Enter bubble (NSMB multiplayer only)

Mario Kart Wii [traditional].ini
--------------------------------
* **Mario Kart Wii**
* Tweaked Classic Controller layout – not exactly as GameCube's Double Dash (Use Item is Y/B there) to make button prompts apply
* Accelerate: A
* Use item: X / LT
* Drift: RT

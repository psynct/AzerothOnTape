# Azeroth On Tape

| OSX | Windows | Latest  | Downloads |
|-----|---------|---------|-----------|
|[![Travis Build Status](https://travis-ci.org/DungFu/OBS-Auto-Record.svg?branch=master)](https://travis-ci.org/DungFu/OBS-Auto-Record)|[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/xxe0gbovybndeeyv/branch/master?svg=true)](https://ci.appveyor.com/project/DungFu/obs-auto-record)|[![Latest GitHub Release](https://img.shields.io/github/release/DungFu/OBS-Auto-Record.svg)](https://github.com/DungFu/OBS-Auto-Record/releases/latest)|[![Total Downloads](https://img.shields.io/github/downloads/DungFu/OBS-Auto-Record/total.svg)](https://github.com/DungFu/OBS-Auto-Record/releases/latest)|

Convert quest text in World of Warcraft to speech using Google text to speech API.

![Azeroth On Tape Screenshot](https://i.imgur.com/rLcKBpI.png)

## How to install
1. Copy Addon in Addon folder to your Interface/Addons folder in your WoW directory
2. Download the latest [release](https://github.com/DungFu/AzerothOnTape/releases) of Azeroth On Tape
3. Run Azeroth On Tape
4. Set keyboard shortcut to use to trigger text to speech and your Google text to speech API key
5. Run WoW and make sure Azeroth On Tape addon is enabled
6. Set keybindings for Azeroth On Tape addon in keybinding section of WoW menu to Shift-F11 and Shift-F12
7. Press you the keyboard shortcut you set in the app and enjoy having all your quests read to you!

## How to compile
### Windows
Install [Microsoft Visual Studio Code](https://code.visualstudio.com/download)
Install [Qt Creator](https://www.qt.io/download) (with corresponding msvsc version in newest Qt version, and make sure to install OpenSSL as well)
```
qpm install
```
Press the run button!

And if you want to move dependencies:
```
windeployqt azerothontape.exe
```
You can also use UPX to compress the DLL files is desired.

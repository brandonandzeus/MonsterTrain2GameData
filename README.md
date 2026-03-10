# MonsterTrain2GameData
Data dumps for Monster Train 2 game data, so AssetStudio no longer needs to be used. This is to help with modding Monster Train 2.
If you are new to modding Monster Train 2, here's a [tutorial]([https://github.com/brandonandzeus/Trainworks2/wiki](https://github.com/Monster-Train-2-Modding-Group/Trainworks-Reloaded/wiki/Getting-Setup-for-Modding)) to get you started.

Data provided for research purposes only.

## Motivation
Using AssetStudio is a pain for searching for GameData objects

1. Asset names do not align with the associated Card/Character/etc. in-game. This is especially true for Artifacts/Relics.
2. Looking up how a specific object works take time and effort. One would need to flip through multiple assets. For instance, CardUpgrades are their assets and must be looked up.
3. When viewing GameData, you see all of the fields, even if they are their default value, making it harder to decipher what fields are important, even more so extra non required fields may also be set (possibly due to devs copy/pasting unity assets and modifying)

## How to use
This repo only contains JSON files, each representing a particular GameData object. The JSON files are minimized, meaning all unimportant fields (and select fields that are set to their default value) are removed. Additionally, the data is expanded from what you would see in AssetStudio, allowing you to easily see how a specific GameData object works or how a particular field is used.

Note that not all fields present in the data are included, file an issue if data you would like to be present is not included.

Note that currently the JSON format this data is in is NOT COMPATIBLE with the official JSON schema for Trainworks-Reloaded, the fields will need to be translated to the appropriate field, but should serve as a gentle hint as to what fields need to be set. (See [#1](https://github.com/brandonandzeus/MonsterTrain2GameData/issues/1))

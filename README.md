# rw-mod-template
A template for a Rain World mod. Made by toxic.echoes (discord).

# mods\mod\modinfo.json
## The modinfo.json file

Use the modinfo.json provided in the repo, and then edit it to your liking. I'll explain each field:

1. ID: The id of your mod.
2. Name: The name of your mod.
3. Description: The description of the mod. use '<LINE>' to make a line.
4. Version: The version of your mod. 1.0.0 is a first release.
5. Requirements: Dependency ids.
6. Requirements Names: Dependency names.
7. Checksum Override Version: Keep this at false. DON'T FUCK WITH THIS!!!!!!!!!

# mods\mod\thumbnail.png
## The thumbnail that appears in-game and on the Steam workshop

Thumbnails are usually 640 x 360. Whilst you can use other dimensions, it may result in unwanted changes (stretched images, quality reductions, etc.)

Put this in the same folder as the modinfo.json!

# mods\mod\plugins
## THIS FOR CODE MODS!!
## The folder where .dll files are placed.

Assuming you have already compiled your .csproj, this is where the .dll file(s) will be put.

# mods\mod\modify
## FOR MODIFYNG THE GAME'S EXISTING FILES
## Used to modify existing game files, add pearls, and add regions

In order to use \modify efficiently, there are a few fields I will go over.

## mod\modify\world
Go here to add regions.txt, which you can add your region acronym. More info here: https://rainworldmodding.miraheze.org/wiki/Creating_A_Region#Regions.txt

## mod\modify\world\hi
Use this modify the properties file, world file, or display name file of the region specified. In this context (HI) we're using Industrial Complex.

## mod\modify\world\hi-rooms
Use this directory to modify rooms. As said, in this context we're modifying Industrial Complex. I'll list the region acronyms in a different file.

# mods\mod\world
## THIS IS FOR REGION MODS, OR ADDING NEW ROOMS TO EXISTING REGIONS
## Where the rooms and folder of a region are placed; most notably modded regions

To add new rooms to a region or make your own, you go here.
If you want to make regions, go here: https://rainworldmodding.miraheze.org/wiki/Creating_A_Region

# mods\mod\decals
## Decals for the mod.
Add custom decals for Dev Tools here.

# mods\mod\music
## Music for the mod.
Add custom soundtracks for Dev Tools here.

# mods\mod\palettes
## Palettes for the mod
Add a new palette to use! Put a number after 'palette'; example, 'palette652.png'

# mods\mod\text
## For translations
Translate text here.


# Conclusion

## Last message!
This is not everything, and I will continously update as needed. Thanks for sticking by; cheers, and have fun making your mod!

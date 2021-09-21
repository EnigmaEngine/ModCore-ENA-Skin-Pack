# ENA Skin Pack for ModCore

An example mod for Enigma Engine which implements the popular "ENA Skin Pack" skins mod. Please use this as a working example to create your own mods.

## Features

This mod features the following:

* Replaces Boyfriend with ENA from Joel G's animations.
  * Includes custom death animation.
  * Includes custom portrait and dialog in Week 6.
* Replaces Girlfriend with Moony from the ENA animations.
  * Includes custom graphic for title screen.
* Replaces Pico with Shephard.
* Replaces the graphic for the main menu background.

## Notes

* `_polymod_meta.json` includes data used for the mod menu.
* `_polymod_icon.png` includes the icon used for the mod menu.
* All other assets use the proper file names and locations of the respective files in the `assets` folder, so that ModCore performs the replacement when the mod loads.
* Animation names and offsets for the animations in the XML file were meticulously made to be identical to those from the base game when the original skins were made, so a replacement of `data/characters/bf.json` is not necessary. When making skins for ModCore, you can simply create any animations with any frame count without having to worry about drawing over the original sprites or even having the correct animation prefixes; simply provide the corrected values in the character JSON file and it will work.
  * Check out an example of [how to make character data JSONs](https://github.com/EnigmaEngine/ModCore-Tricky).

## Licensing

The ENA Skin Pack is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License](https://creativecommons.org/licenses/by-nc-nd/4.0/). It was created by [rhubarb](https://gamebanana.com/members/1773224) on GameBanana and was originally uploaded [to this page](https://gamebanana.com/mods/186934). 

This repository redistributes this skin pack in a different format, with additional data to allow it to be used with the Enigma Engine ModCore system. CC licenses grant permission to use the licensed material in any media or format regardless of the format in which it has been made available.

If you are the original licensor for some or all of the content available here, please contact me with sufficient proof of ownership and a request to take down the repository.


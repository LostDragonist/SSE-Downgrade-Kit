## SSE-Downgrade-Kit

## Why does this repo exist?

On 11/11/2021, Bethesda released The Elder Scrolls V: Skyrim - Anniversay Edition and updated the game from 1.5.97 to 1.6.xxx. This changed modding in such a way that would forever create a schism between the 1.5.xxx versions and 1.6.xxx versions. That means sometimes you want one and sometimes you want the other.

[Wabbajack](http://www.wabbajack.org/) (WJ) is usually able to convert automatically convert between different versions of the game with a bit of binary patching but some changes are so extreme that's not really the case. This repo serves to remedy that problem.

## How do I use this?

1. Structure your game install as a "stock game install". (You can skip this if you already do all this.)
   * Delete your `Skyrim Special Edition` game folder.
   * Install the version of the game you want to mod with [Unofficial Skyrim Downloader](https://www.nexusmods.com/skyrimspecialedition/mods/61756) (or through some other method).
   * In your WJ folder with all the MO2 files, create a new folder called `Stock Game`. The exact name isn't important but this is the convention.
   * Copy all the files from your Steam's `Skyrim Special Edition` folder to this `Stock Game` folder.
   * Configure MO2 to mod this game folder instead of Steam's folder.
2. Set up the downgrade kit.
   * Download the latest versions of [SSE.Downgrade.Kit.7z](https://github.com/LostDragonist/SSE-Downgrade-Kit/raw/main/SSE.Downgrade.Kit.7z) (click to download) and [SSE.Downgrade.Kit.7z.meta](https://raw.githubusercontent.com/LostDragonist/SSE-Downgrade-Kit/main/SSE.Downgrade.Kit.7z.meta) (right-click and `save as...` to download).
   * Put those files in your downloads folder.
3. Inline Bink
   * Dowload the latest version of [WABBAJACK_NOMATCH_INCLUDE_FILES.txt](https://raw.githubusercontent.com/LostDragonist/SSE-Downgrade-Kit/main/WABBAJACK_NOMATCH_INCLUDE_FILES.txt) (right-click and `save as...` to download).
   * Put this file in your `Stock Game` folder.
4. Compile like normal with WJ!

## How well does this work?

Following the exact instructions above, the .wabbajack file ends up being about 2 GB in size. That's with just MO2, the game, and no mods. If you're using a mod like [Cleaned Skyrim SE Textures](https://www.nexusmods.com/skyrimspecialedition/mods/38775), or something else that replaces literally every texture in the game, then you can delete the `Skyrim - Textures X.bsa` files from your `Stock Game` folder. This will result in a .wabbajack only 133 MB in size.

## Do you have permission to do this?

Good question! I have no idea. I'm just betting on the idea that Bethesda et al. isn't really going to care if host a few files from old versions of their game in order to support people buying and playing their games. This certainly isn't the most egregious use of vanilla files in the modding world. /shrug. Let me know if I need to take them down.

That said, all files in this repo should be considered copyrighted by Bethesda Game Studio unless otherwise mentioned.

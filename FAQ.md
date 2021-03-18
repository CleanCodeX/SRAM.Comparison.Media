##Q: What's the Evermore Format Exploration Project?
> A: The S-RAM-file can be generally read and manipulated. Although that's good, the only problem is that some parts of SoE's save slot format are still considered to be unknown, meaning that we don't really know what those bytes control. To change that some SoE fans started a project to create a complete documentation, usually called Rosetta Stone. A RAMsetta Stone if you will.

###Q: What are the goals?
> A: If the S-RAM format is completely known, a future savegame editor can enable/disable everything what is controlled by a savegame.

####Q: What are possible features of such a savegame editor?
> A: Most likely candidates are:
> * Reset of (already performed) boss fights
> * Reset suspended ingredients for a map, chapter or the whole game
> * Reset opened boxes, pots and gourds or walls for a map, chapter or the whole game
> * Specifying the in-game save point location where your savegame should continue from

####Q: When will it be available?
> A: Well, that's mostly up to the amount and quality of contributions by the community.
We are spending our free time achieving that, but we alone won't be enough to finish format exploration it in the near future.

If you want to speed up the process and explore S-RAM by yourself, see [here](exploring) how it works.

####Q: What's S-RAM Comparer?
> A: S-RAM Comparer is available both as a Windows console app and as a web app. S-RAM comparison is WAY more easier than before. 
> This app allows to compare (unknown) areas and modify offset values in Secret of Evermore's S-RAM file.

####Q: What are the Unknowns?
> A: An explanation of what unknowns are can be found in the [glossary](glossary). 
> A non-exhaustive list of examples can be found under: [unknowns](unknowns).

####Q: What are the main features?
> A: 
Comparison related
> * [C|W) Comparison of *.SRM files as well as Snes9x savestate files  
> * [C|W) Comparison of Unknowns areas / complete save slot area
> * [C|W) Comparison of either specific slots only or all slots at once
> * [C|W) Export comparison result as text file
> * [C) Optional file watcher (windows) to compare S-RAM when you create a savestate / save in-game
> * [C|W) Display value differences in decimal, hex and binary format
Offsets
> * [C|W) Show/Edit specific *.SRM offset values
> * [C|W) Show offset values from savestates
Misc
> * [C|W) Display and Export save slot summary
> * [C) Backup / restore functionality of current and comparison S-RAM file

*) C = Supported by [Windows Console App](console-app)
*) W = Supported by [Web App](comparison)

####Q: Which file type types are supported?
> A: Currently supported are *.SRM-files and Snes9x' savestate files

####Q: Can we see some imagery?
> A: For images of console app see [here](imagery).

####Q: Is there a guide?
> A: Yes, see [here](guides).

####Q: Does S-RAM Comparer (SoE) support other games than SoE?
> A: Currently not. Although the S-RAM comparison library is game independent, this version is specific for Secret of Evermore's savegame format.

####Q: Is this open source?
> A: Yes, for source code see [here](https://github.com/CleanCodeX). Feel free to contribute!

####Q: Is there support for other games in the future?
> A: Other games will likely be supported in the far future, as well as a version that is completely game-independent in terms of code and based on format files. If you're a developer feel free to make a fork for your favorite game anytime. You will most likely get support afterwards.

####Q: How can my favorite game be the next?
> A: If there's a demand for supporting a specific game, address your wish in the [community](Community).
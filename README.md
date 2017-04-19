![Logo](logo.png)

# Puyo Puyo Tetris English Translation for 3DS

*by. Ongo Gablogian*

__A somewhat basic English translation for Puyo Puyo Tetris for the Nintendo 3DS.__


[More info here.](https://gbatemp.net/threads/wip-puyo-puyo-tetris-english-translation-looking-for-help.434967/)



## Installation Instructions:


__Luma3DS v7.0 and above:__

- Rename the “Translated Files” folder to “romfs” and move to "SD:/luma/titles/0004000000101200/".

- Enable the “Enable game patching” option in the Luma3DS config menu.


__Build As A CIA:__

- Dump your copy of Puyo Puyo Tetris (physical or digital) and extract the files.

- Copy everything from the “Translated Files” folder and merge it with the extracted RomFS.

- Copy the included "banner.bin" and overwrite the original located in the extracted ExeFS.

- Rebuild as a CIA and install.


__BootNTR & LayeredFS/OnionFS:__

- Place the proper LayeredFS file (either v1.0 or v1.1 depending on your game update version) in "SD:/plugin/0004000000101200/". 

- Rename the "Translated Files" folder to "PuyoPuyoTetris" and place it on the root of your SD. 

- [OnionFS](https://github.com/mariohackandglitch/OnionFS) can be substituted for LayeredFS if desired. The default path is "SD:/OnionFS/0004000000101200/romfs/".

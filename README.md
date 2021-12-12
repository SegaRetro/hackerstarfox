# HackerStarFox
Star Fox (SNES, 1993), with modifications for easier creation of ROM hacks 

## Features

- SuperFX 2 support and various optimizations
- Lots of free bank space for new models, assets and code
- Bugfixes and improvements
- rebuild color palette data using the palette packer (bldpal.bat)
- Easier creation of wireframe models
- Kando was involved so you know it's good
- Matching German Script
- (not yet, but will be) Starwing title screen

## Building

Building is easy if you've used the Star Fox EZBuild.  
This repo is intended for building on Windows, but can probably be easily modified for other platforms.

## Helpful Links

[Star Fox - Source Code Mods](https://docs.google.com/document/d/1kdgPCBeQFYsAepSDNpmwO8ZysRJjdnwK_5gWT2FFQEk/edit?usp=sharing)  
[Star Fox Mods Wiki](https://starfox-mods.fandom.com)  
[65c816 reference](https://en.wikibooks.org/wiki/Super_NES_Programming/65c816_reference)  
[SuperFX ASM Tutorial/Reference](https://en.m.wikibooks.org/wiki/Super_NES_Programming/Super_FX_tutorial)

## Discord Server
[Star Fox: ES + SF Modding](https://discord.gg/fE5Xx99kWb) (MAIN)  
[Star Fox Hacking Project](https://discord.gg/GgyP84e)


## Future things to do
~~1. Fix debug mode crash~~ turns out it's not a crash or a softlock, just hold P2 L until debug UI reappears  
1. OPTIMIZE
2. Expanded texture space
3. Annotate and document code
4. FastROM
5. Organize source files and edit makefile accordingly

## Project Structure
```
hackerstarfox
├── BIN: exe files needed to compile game
├── optionalstuff: optional graphics files
├── SF: Main source code is located here
│   ├── DATA: GFX files, arc tangent table
│   │   └── GFX: Palette files and Palette Packer
│   ├── MAPS: level scripts
│   ├── MSPRITES: contains 4 DAT files (interleaved textures)
│   └── SOUND: sound/music data
└──  tools: tools such as packer and ShapeEd
```
    

# Better Command Blocks
Adds command blocks similar to those of a certain other voxel game (hereafter referred to as ACOVG). It is the only command block mod to support my [Better Commands](https://github.com/thepython10110/better_commands) mod. It includes impulse, repeating, and chain command blocks, and *should* be game-agnostic (although you kind of need Mesecons/redstone for impulse command blocks to be useful).

To use the command blocks, you must have the `better_command_blocks` privilege.

Normal commands (not Better Commands) can *only* be run if the placer is online, and are executed as the placer. Better Commands are executed as the command block itself 

## License:
* Code: Licensed under MIT
* Textures: Created by me, inspired by ACOVG's (and various ACOVG texture packs that I considered using instead), and licensed under CC-BY-SA-4.0

## Known issues:
1. If a command block is about to run a command after a delay, and it is dug before the delay is over, it will still run. This also applies to bulk command blocks.
2. While commands can *mostly* be used with or without slashes, they are REQUIRED if the command has multiple slashes (such as `//replace` from WorldEdit).
4. Internally, command blocks *technically* face backwards because I accidentally made it that way. This will not be fixed, because it really has no effect besides potentially slightly confusing people who look at the code.
5. I skipped 3.
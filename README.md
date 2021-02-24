A list of scripts with a variety of usecases ranging from handling common desktop environment functions to extracting titles and IDs from nintendo roms to installing operating systems. I write them for my needs, and with my environment in mind, but they should be fairly adaptable for anyone else's use, and I would like to maintain them so that remains true, so please submit issues if you'd like. All the scripts in this repo are posix shell.

## noteable scripts
### spidystrap
A minorly interactive script for installing arch linux locally from an arch linux environment, with the help of a config file (which it can generate). It has kinks and needs a revision... but it *does* work!!

### ninid
grabs the internal title and ID (if applicable) of a GB/GBC/GBA/NDS game rom, and prints it.

### update-mirrorlist
with the help of rankmirrors from the pacman-contrib package, grabs the latest local pacman mirror list, then ranks them from best to worst connection.

### outsort
outsort is a tool meant to aid cleaning up dirty downloads folders! by default, it will never overwrite the files it tries to move. it operates mostly in dmenu and specified file previewers, but you should probably run it form the command line so you can see and interact with the output if need be.

### gamerename-redux
this is a tool for renaming games and simultaneously their save data(s). I rewrote this completely from my dmenu_gamerename script, because I wanted it to be more adaptable. How it works: usage: gamerename-redux [rom path] [save path] or else, rom path and save path will default to what they are set to in the configuration section below. [rom path] can be a game, or it can be a directory containing games, in which case a dmenu prompt will ask you to locate the desired game further down the folder tree. Once you locate the game, the directories you navigated will be reflected in the save path, and renaming the game will also rename all save files of the same name (not counting their file extensions). Also, you can specify [rom path] as an argument without specifying [save path], and it will use the default save path.


### launch-\*, dmenu_\*
these are scripts I use in my desktop environment for various things. The one I think I'm most proud of is launch-game!

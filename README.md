A list of scripts with a variety of usecases ranging from handling common desktop environment functions to extracting titles and IDs from nintendo roms to installing operating systems. I write them for my needs, and with my environment in mind, but they should be fairly adaptable for anyone else's use, and I would like to maintain them so that remains true, so please submit issues if you'd like. All the scripts in this repo are posix shell.

## noteable scripts
### spidystrap
A minorly interactive script for installing arch linux locally from an arch linux environment, with the help of a config file (which it can generate). It has kinks and needs a revision... but it *does* work!!

### ninid
grabs the internal title and ID (if applicable) of a GB/GBC/GBA/NDS game rom, and prints it.

### update-mirrorlist
with the help of rankmirrors from the pacman-contrib package, grabs the latest local pacman mirror list, then ranks them from best to worst connection.

### launch-\*, dmenu_\*
these are scripts I use in my desktop environment for various things. The one I think I'm most proud of is launch-game!

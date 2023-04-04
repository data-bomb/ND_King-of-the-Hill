# [ND] King of the Hill

A SourceMod gamemode plugin for Nuclear Dawn.

## Description:
Teams fight over control of the Primary Resource Point in timed round matches.
The team who controls Prime for the longest amount of time will win the round.

## Installation:
- Install the `[ND] Commander Structure Intercepts` plugin (https://forums.alliedmods.net/showthread.php?p=2796149)
- Ensure the `build-structure.games.txt` file is in the addons/sourcemod/gamedata/ directory
- Copy the `nd_king_of_the_hill.smx` file to the addons/sourcemod/plugins/ directory
- Copy the `commander-abilities.games.txt` file to the addons/sourcemod/gamedata/ directory
- Copy the `resource-points.games.txt` file to the addons/sourcemod/gamedata/ directory
- Copy the `terminate-round.games.txt` file to the addons/sourcemod/gamedata/ directory
- (Optional) Add `mp_roundtime 15` to the cfg/server.cfg file
- (Optional) Add `mp_maxrounds 4` to the cfg/server.cfg file
- (Optional) Add `sv_tags "kingofthehill"` to the cfg/server.cfg file

## Gameplay Features:
- Turns off all tertiary and secondary resource resource points
- Increases trickle income from 1,200/minute to 3,600/minute
- No offensive buildings within 1,300 distance of primary resource point
-- (No spawns, turrets, artillery, or walls)
- No artillery shelling within 900 distance of primary resource point
- No commander abilities within 900 distance of primary resource point
- No building on the enemy side of the map
- Make starting map structures invulnerable to sieging
- Make new structures harder to destroy
- Force bots to capture/defend main point only
- Limit nades for team defending prime
- Reports score in HUD

## Compilation / Dependencies:
- Place `morecolors.inc` in addons/sourcemod/scripting/include [https://github.com/Bara/Multi-Colors]

## Future Considerations:
- Add colored chat messages
- Add reminders of King of the Hill mode
- Add translations support
- Improve balance

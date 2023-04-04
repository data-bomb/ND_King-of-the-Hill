# [ND] King of the Hill

## Description:
Teams fight over control of the Primary Resource Point in timed round matches.
The team who controls Prime for the longest amount of time will win the round.

## Gameplay Features
### Focus on Players Taking Prime
- Tertiary and Secondary resource points may not be captured
*(Bots will only try and capture and defend Prime)*
- Stops offensive buildings within 1,300 distance of primary resource point
*(No spawns, turrets, artillery, or walls)*
- Stops artillery shelling within 900 distance of primary resource point
- Stops commander abilities within 900 distance of primary resource point
- Stops all building on the enemy side of the map
- Starting structures are invulnerable
### Economy Changes
- Increases trickle income from 1,200/minute to 3,600/minute
- Earn 500 resources for each kill when attacking Prime
### Balance Changes
- Make new structures slightly harder to destroy
- Limit nades for team defending prime
### Miscellaneous Changes
- Reports score in HUD

## Installation Steps:
- Install the `[ND] Commander Structure Intercepts` plugin (https://forums.alliedmods.net/showthread.php?p=2796149)
- Ensure the `build-structure.games.txt` file is in the addons/sourcemod/gamedata/ directory
- Copy the `nd_king_of_the_hill.smx` file to the addons/sourcemod/plugins/ directory
- Copy the `commander-abilities.games.txt` file to the addons/sourcemod/gamedata/ directory
- Copy the `resource-points.games.txt` file to the addons/sourcemod/gamedata/ directory
- Copy the `terminate-round.games.txt` file to the addons/sourcemod/gamedata/ directory
- (Optional) Add `mp_roundtime 15` to the cfg/server.cfg file
- (Optional) Add `mp_maxrounds 4` to the cfg/server.cfg file
- (Optional) Add `sv_tags "kingofthehill"` to the cfg/server.cfg file

## Compilation Dependencies:
- Place `morecolors.inc` in addons/sourcemod/scripting/include [https://github.com/Bara/Multi-Colors]

## Future Considerations:
- Add colored chat messages
- Add more reminders of King of the Hill mode
- Add translations support
- Improve balance

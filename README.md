# [ND] King of the Hill

A SourceMod gamemode plugin for Nuclear Dawn.

## Description:
Teams fight over control of the Primary Resource Point in timed round matches.
The team who controls Prime for the longest amount of time will win the round.

## Installation:
- Install the `[ND] Build Structure Intercept` plugin (https://forums.alliedmods.net/showthread.php?p=2796149)
- Ensure the `build-structure.games.txt` file is in the addons/sourcemod/gamedata/ directory
- Copy the `nd_king_of_the_hill.smx` file to the addons/sourcemod/plugins directory
- Copy the `commander-abilities.games.txt` file to the addons/sourcemod/gamedata/ directory
- Copy the `resource-points.games.txt` file to the addons/sourcemod/gamedata/ directory
- Copy the `terminate-round.games.txt` file to the addons/sourcemod/gamedata/ directory
- (Optional) `mp_roundtime 15`
- (Optional) `mp_maxrounds 4`

## Gameplay Features:
- Turns off all tertiary and secondary resource resource points
- No building within x distance of primary resource point
- No artillery shelling within x distance of primary resource point
- No commander abilities within x distance of primary resource point
- No building too close to enemy bunker - action is in the middle
- Make starting map structures invulnerable to sieging
- Make new structures harder to destroy
- Force bots to capture/defend main point only
- Limit nades for team defending prime

## Future Considerations:
- Add translations support
- Improve balance

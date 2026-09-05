SpaceRadiant v1.4.3

Changes from v1.4.2:
- Player starts at the center of the 800x1700 map.
- Enemy spawning is spaced about 2 seconds apart to reduce frame spikes/freezes.
- Enemy spawn positions are checked against walls so enemies do not spawn inside walls.
- Splitter shards also use safe spawn positions.
- EXP drops disappear after 10 seconds if not collected.
- Safer EXP magnet calculation when the player is exactly on a drop.
- HUD/skill DOM updates are throttled to reduce mobile/TV browser load.
- Keeps the previous wall line-of-sight auto-fire behavior and enemy boundary protection.

Run on Termux port 9999 using the server included with your setup.

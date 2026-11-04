# LR2 Plus releases

The newest is in `latest/`; the launcher downloads its files from the folder named by its tag.

## v332

- ORBIT FIX now also stops the game's own homing missiles spinning after they touch something
- That spin was why they circled their targets: bench hits went from 25-48% to 52-83%

## v331

- New, experimental: WEAPONS > MISSILE PATHFINDING: ADVANCED - homing missiles follow the track's map
- They fly over the cars (MISSILE HEIGHT, 3.5 m) and pass through things until they see their target
- Then they come down to its level and turn solid; checkpoints never stop them
- Bench: 65-88% of advanced missiles hit their target on 4 tracks (the game's own: 25-48%)
- The track's map is now also made for the missiles (online: in the background, no wait)
- Launcher v97: Missile pathfinding and Missile height rows

## v330

- New, experimental: CARS > PATHFINDING: ADVANCED - CPUs work out each track from its checkpoints
- The first race on a track maps it (a few seconds, the race waits); it's remembered after that
- CPU personalities: smooth, short or flat lines at random; only short-line CPUs take small shortcuts
- PATHFINDING HINT (on): a second route along the game's CPU line - finds Xalax 1's loop
- CPUs know the ground's grip (Arctic's ice) and keep inside the track getting back to their line
- ADVENTURE PATHFINDING: the same for the adventure's races, set separately
- Online races: AUTODRIVE ON / OFF for your own car in the race menu (Start / Esc)
- Launcher v96: Pathfinding, Adventure pathfinding and Pathfinding hint rows


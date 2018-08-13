# MyUnrealRandomRoomProject
A random room selector in unreal engine 4.20.1

This map has a trigger box that will pull one of 2 random maps into the doorway, resulting in a near infinite map of random rooms.  This is an map generater example, and will not include an actual game, or art, or really anything except for the code to generate the rooms. 

Bugs:

1. After a certain distance from the center of the map, the navmesh will stop working.  It has a limited range.
2. Rooms may spawn over each other resulting in a blocked passageway.

TODO:

1. Make more rooms.
2. Spawn further ahead.  Currently only spawns the next room.
3. Build a list / table of rooms with other details that can control what will spawn.
3. Store a room tree, and release older rooms? (Only keep loaded the nearest rooms to the player)
4. Check area for space to place room before placing a room, and change room or make a dead end room to keep overlap from happening.
5. Redirect or stop rooms that get too close to the navmesh boundry.


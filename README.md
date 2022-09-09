# AI-Editor
Note: This project is very new, and there may be a few odd bugs that I haven't seen. It would be appreciated if these were reported.

This is an attempt at a basic AI editor, which provides tools in a canvas sandbox. The models are *EXTREMELY* simple (just rectangles), however, you can make them more complicated 
along with collisions too. There are 3 main classes which can be used to develop an AI from this:
1. Player. The Player class creates one controllable player (you) and then you can create dummy players from it, which can be used to help enemy AI targetting on multiple players.
2. Enemy. The Enemy class provides data that can be used for, well, enemy AI. It contains data such as positions, model, and stats such as health. 
3. Wall. The Wall class creates a rectangular wall of specified dimensions, which contain basic rectangular collisions. This allows for more complicated AI that react to structures.

 There is also a fourth class for a weapon system which I made. That can only be used by players as a way of play testing sort of. You can damage enemies with them. The weapon system I made simply rotates a projectile around the player. I encourage you to make something even better from this!
 
 The AI Editor's entire code (or currently 98.1% of it) is put into an HTML script, and all variables are public and editable from console. 
This allows you to edit existing data and push new data (such as instantiating new enemies), all from the console.
Most of this stuff is detailed from comments within the code, and the project runs on localhost:3000.

 Also, if anyone wants to help work on this (which I would greatly appreciate, I haven't been able to since school started back up [and there are still a few core things I haven't finished], please contact me through Discord. My tag is @Occ#7585. Feel free to just dm me telling me you want to join the project, and there's a few wanted things that I have below.
 
 Continuing my last paragraph, here's a list of current things that I need/want in this:
 1. Camera movement. Right now, it's just a canvas that the player can move along. I want to make it more like a real io game and add a simplistic camera system to the canvas, which will make it more like an authentic io game.
 2. More complicated models. Right now, all the models I have are just squares and rectangles. Although this is good for walls, elliptical shapes (with some extra design on them maybe, like eyes on the players for example) are prefereable for the weapons, players, and enemies.
 3. More complicated collisions. With more complicated models, collision math will need to be updated. Along with this, Currently collisions don't actually have some sort of physics to push something away from something else (except for walls, which already have collision math to stop players and enemies from going through them in a smooth manner). More complicated physics would be appreciated.
 4. More AI examples. Currently, I only have one named Smasher. Any more cool AI would be appreciated.
 



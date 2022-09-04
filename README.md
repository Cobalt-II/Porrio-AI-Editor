# AI-Editor
Note: This project is very new (only two days old at the time I'm writing this), and I only posted it here a few hours ago. There may be a few odd bugs that I haven't seen. It would be appreciated if these were reported.

This is an attempt at a basic AI editor, which provides tools in a canvas sandbox. The models are *EXTREMELY* simple (just rectangles), however, you can make them more complicated 
along with collisions too. There are 3 main classes which can be used to develop an AI from this:
1. Player. The Player class creates one controllable player (you) and then you can create dummy players from it, which can be used to help enemy AI targetting on multiple players.
2. Enemy. The Enemy class provides data that can be used for, well, enemy AI. It contains data such as positions, model, and stats such as health. 
3. Wall. The Wall class creates a rectangular wall of specified dimensions, which contain basic rectangular collisions. This allows for more complicated AI that react to structures.

 There is also a fourth class for a weapon system which I made. That can only be used by players as a way of play testing sort of. You can damage enemies with them. The weapon system I made simply rotates a projectile around the player. I encourage you to make something even better from this!
 
 The AI Editor's entire code (or currently 98.1% of it) is put into an HTML script, and all variables are public and editable from console. 
This allows you to edit existing data and push new data (such as instantiating new enemies), all from the console.
Most of this stuff is detailed from comments within the code, and the project runs on localhost:3000.



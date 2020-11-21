# LASER DODGE

You find yourself in quite a precarious predicament... surrounded by an electrically charged wall, caught in the crossfire of six laser turrets!
The only way to hold off your inevitable demise is to dodge the lasers for as long as you can.

## CONTROLS

Arrow keys or WASD to move.
Escape to quit.

## AUTHORS AND ACKNOWLEDGEMENT

Author: Brandon Marconet
Credit for many of the code's functions to Colton Ogden.
"Spy/Secret Agent Loop" music credits to Sirkoto51 on freesound.org.

## DETAILED INFORMATION FOR CS50X FINAL PROJECT SUBMISSION

Laser Dodge is an action game with 3x3 grid-based movement where you must dodge lasers that fly across the screen.

Character movement is restricted to a 3x3, which decreases in size as the game progresses. Pressing the arrow keys
or WASD keys will move the character to the neighboring grid in the appropriate direction. The tiles immediately
neighboring this grid are electrically charged - that is, moving onto them will trigger the character's death.

Laser beams spawn from 6 turrets on the map - 3 above and 3 to the right. The rate of laser beam spawning is fixed,
and gets quicker as the game progresses. The turret from which a laser beam emerges is randomly selected by the code.
Dimensions and direction of laser beams vary on whether they emerge from one of the turrets at the top of the screen
or at the right of the screen. These beams were coded in Lua using a table - a row is added to the table when the 
beam spawns, and is removed from the table when its beam leaves the window.

Score increments as each laser beam leaves the window. This score is displayed at the top right of the screen. The 
score is also featured in the center of the game over screen.

The game utilizes three game states - one for the title menu, one for gameplay, and one for the game over screen. The 
user may press 'Return' at either the title menu or the game over screen to start the game. The user may press 'Esc'
in any state to close the game.

I created the atlas / character sprite on pixilart.com. I created sound effects using bfxr software. Music was 
taken from freesound.org, as credited above.

Screenshots of the game can be found at the following Google Drive location:
https://drive.google.com/drive/folders/1931zbsQF6ltvmVBdZGOj8nHsfz1AdKNb?usp=sharing

Game uploaded to the following Github location:
https://github.com/TheKillerCucumber/LASER-DODGE

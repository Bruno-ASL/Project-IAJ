
# Project-IAJ

  

**Little Rogue** is a roguelike game made with python and pygame library,
it feature all basic roguelike gameplay
such exploration of random generated dungeon, fighting monsters,
gaining experience and picking up items on the ground... etc

  
##
## Player Controls

**Movement:** Use the arrow keys to move the player character (@) in the cardinal directions:
- Up Arrow: Move north (up).
- Down Arrow: Move south (down).
- Left Arrow: Move west (left).
- Right Arrow: Move east (right).

**Attack:**
- Move into a monster's tile to automatically initiate an attack.

**Pick Up Items:**
- G key: Pick up an item from the ground if the player is standing on an item tile.

**Inventory:**
- I key: Open the inventory menu to manage items:
	- Use the arrow keys to navigate through inventory items.
	- Press the corresponding key displayed next to an item to use it.
	- Press any other key to cancel.

**Drop Items:**
- D key: Drop an item from the inventory onto the ground.

**Character Information:**
- C key: Display the character's current level, experience, HP, attack power, and defense.

**Stairs:**
- < or . key: Descend to the next level if standing on the stairs (< or > symbols on the map).

**Miscellaneous:**
- Escape key: Pause the game and open the main menu.
- Mouse click: Move the player character to the clicked location on the screen.
	- Left-click: Initiate movement towards the clicked tile.
	- Right-click: Display names of objects under the mouse cursor.

##
## Game State and Navigation

**Main Menu:**
-	Use arrow keys (Up and Down) to navigate between menu options.
-	Press Enter to select an option:
	- Play a new game: Starts a new game session.
	-	Continue last game: Resumes the last saved game session.
	-	Quit: Exits the game.
	
##
## Game Mechanics
**Combat:**
- Players and monsters engage in turn-based combat.
- Moving into a monster's tile initiates an attack sequence.

**Inventory Management:**
- Collect and manage items found throughout the game.
- Use or drop items as needed.

**Leveling Up:**
- Gain experience by defeating monsters.
- Automatically level up upon reaching the required experience threshold.

**Game Over:**
- If the player character's HP drops to zero, the game ends.

##
## User Interface

**Message Log:**
- Displays game messages such as combat outcomes, item pickups, and interactions.

**GUI Elements:**
- Health bar and other character stats are displayed to track player status.

##
## Additional Notes

  

**Camera:**
Automatically follows the player character (@) around the game map.

  

**Save and Load:**
Games can be saved and loaded through the main menu.

##
## Objectives
Implement behaviours that can achieve the following objectives:
- Complete six levels.
- Defeat the enemies.
- Pick up the items (potions and scrolls). 
- Use the items.

To achieve this, we must use the most appropriate architecture to solve the problem and pay attention to the representation and decision-making technique selected.
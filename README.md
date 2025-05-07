# ATB System (CAGD280)

 ## About This Project

 This is an Active Time Battle (ATB) system meant to replicate the combat in the original Final Fantasy 7. Built in Unreal 5.5

 ## To Start

 Play the build, or load the project in Unreal Engine and hit the 'Play' button. You will start as a 'Warrior' pawn.
 Use WASD to approach the lone enemy on the field -- the orange 'Bandit' in front of you.
 When in range, the ATB battle system will begin.

 Using the mouse, select 'Attack' when prompted, then select an enemy to attack.

 ## Key features
    - UI that dynamically loads players and enemies into various submenus 
	- General color and style of the UI in Final Fantasy 7.
	- Turn-based system that sets turn order and resets turn based on Speed stat
	- Dealing damage based on a Strength stat and other modifiers
	- Player's health is displayed dynamically (MP & health bar to come)
	- Dead enemies are removed from view, attack order, and UI
	- Return to Level_1 when all enemies are dead
	- Cameras that switch based on who is currently attacking

 ## To do
	[ ] Fix spawning into Battle_Plane: works in Dev, breaks Build
	[ ] Feedback on attacks
	[ ] HP & MP Bars
	[ ] Magic, Skills, Items
	[ ] Equipment, Elements, Class Skills
	[ ] Victory menu; adding items and money
	[ ] Saving health between levels (use GameInstance)
	[ ] Status ailments - in and out of battle
	[ ] Menu to Save, Load, Exit, etc.
	[ ] Dynamic variables for Models/Sprites, Animations

> [!NOTE]
> Currently only the basic 'Attack' function works. I plan to implement Magic and Skills, which will utilize the same events and functions as the base Attack.
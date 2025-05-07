# ATB_System_CAGD280
 An Active Turn-based system for RPG built in Unreal, made for CAGD 280 @ CSU Chico

 ## About This Project ##

 This is an Active Time Battle (ATB) system meant to replicate the combat in the original Final Fantasy 7.

  ++ To Start ++ 

 Play the build, or load the project in Unreal Engine and hit the 'Play' button. You will start as a 'Warrior' pawn.
 Use WASD to approach the lone enemy on the field -- the orange 'Bandit' in front of you.
 When in range, the ATB battle system will begin.

 Using the mouse, select 'Attack' when prompted, then select an enemy to attack.

Key features
    - UI that dynamically loads players, enemies, attacks into various submenus.
	- Turn-based system that sets turn order and resets turn based on Speed stat
	- Dealing damage based on a Strength stat
	- Player's health is displayed dynamically
	- Dead enemies are removed from view, attack order, and UI; returns to Level_1 when all enemies are dead
	- Cameras that switch based on who is currently attacking

To do
	[ ] Feedback on attacks
	[ ] Magic, Skills, Items
	[ ] Equipment, Elements, Class Skills
	[ ] Victory menu; adding items and money
	[ ] Saving health between levels (use GameInstance)
	[ ] Status ailments - in and out of battle
	[ ] Menu to Save, Load, Exit, etc.
	[ ] Dynamic variables for Models/Sprites, Animations

 -- Notes --

 -Currently only the basic 'Attack' function works. I plan to implement Magic and Skills, which will utilize the same events and functions as the base Attack.
 -This is a simple-looking projet, but it is built to populate Heroes and Enemies into the UI dynamically. This means that I can create party switching systems and spawn different enemies, and not have to reprogram the entire UI each time.
 -Currently there are no animations; I considered making simple ones using Timelines, but thought I might as well wait until I iterate on this later. I plan to go back to this and build upon it until it is usable later on.
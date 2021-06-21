# MiniRogue_Game

*Code could not be posted online as this code is a solution for a class assignment.*

Character-based C++ game.

   Table of Contents
   -----------------

   1. Introduction 

   2. Game Details

   3. Controls

   4. What I Learned
   
   5. Video Demo 


1.) Introduction 
   --------------------------------
   
This MiniRogue game is modeled after the original Unix Rogue game. In the game, the player's objective is to find a golden idol while navigating a series of dungeons. The player will run into monsters, find items, and descend staircases during the journey. 

The MiniRogue dungeon is 5 levels deep. When the game starts, the player is placed on level 0; the deepest level is level 4.
At the start of a new game and every time the player takes a stairway down, a new level is randomly generated.

2.) Game Details 
   -------------------
   
The player is shown on screen as an **@**.

The different types of monsters that you may encounter and their corresponding symbols are below:

Bogeymen (shown on screen as a **B**)\
Dragons (shown on screen as a **D**)\
Goblins (shown on screen as a **G**)\
Snakewomen (shown on screen as an **S**)

The different types of objects you may encounter are below:

Impenetrable walls (shown on screen as **#**)\
Stairways down to the next level (shown on screen as **>**)\
The golden idol (shown on screen as **&**)\
Weapons (all weapons are shown on screen as a **)** character)\
Maces\
Short swords\
Long swords\
Magic fangs of sleep (that put an opponent to sleep)\
Magic axes (that hit an opponent more often than regular weapons)\
Scrolls (all scrolls are shown on screen as **?**)\
A scroll of teleportation (when read, randomly moves the player)\
A scroll of improve armor (when read, makes it harder for monsters to hit the player)\
A scroll of raise strength (when read, makes a player's blows more effective)\
A scroll of enhance health (when read, raises maximum hit points)\
A scroll of enhance dexterity (when read, makes it more likely the player will hit an opponent)

3.) Controls 
   ------------
 
Move one space using the **arrow keys** or the classic Rogue movement letters:\
**h** to move left\
**l** to move right\
**k** to move up\
**j** to move down

Attack a monster next to you by moving in its direction.

Pick up an object by standing on it and typing **g**.

Wield a weapon by typing **w** and then selecting a weapon from your inventory.

Read a scroll by typing **r** and then selecting a scroll from your inventory.

See an inventory of your items by typing **i**.

When standing on a stairway, descend deeper into the dungeon by typing **>**.

Quit the game by typing **q**.

Cheat by typing **c**. This command sets the player's characteristics to make defeating monsters easy, and exists solely to let us test some aspects of your program without 
our having to slog through a regular game.

If you type something not on this list, you do nothing for this turn, but the monsters take their turn.

4.) What I Learned
   ------------

During this project, I applied many fundamental CS concpets to create a playable game. Some of the concepts I incorporated include but are not limited to: classes, constructors, destructors, inheritance, polymorphism, recursion, and function time-complexity. 

5.) Video Demo
   ------------

https://youtu.be/Pa0JV9_BrFA

------------------------------------------------------------------------
Created by Nicholas P. Dean on 9/9/20.
Copyright © 2020 Nicholas P. Dean. All rights reserved. 
------------------------------------------------------------------------

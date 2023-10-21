# RPG-Sim
A coding assignment for my CSC 1350 class. It's almost impossible for the goblin to win but the numbers can't be readjusted to make the goblin a little more powerful since my professor wanted consistency accross projects. The following text is from the README.txt file that I submitted with my code for my assignment.

I am submitting the RPG assignment for a total of 96 pts. 

Generating random numbers in Java between an origin and a bound the origin is inclusive and the bound is exclusive. To get around that I increased all of the bounds by 1 in my code. So plsplsplspls don't take off points because my code says that the fireball does between 10-26 and my heal does between 20-31 and etc, it's on purpose :,).

When the player is at full health I decided that the player can't heal themselves, however, if they have a little booboo and they heal themselves and the health points exceed 100 after the heal then they're healed back to their max health. The game also informs the player that they are at max health afterwards instead of printing that their health is 100/100. I also decided that if the player or the goblin are hit and their health totals for less than 0 then their health is readjusted to 0.

If the player does not have enough mana for a move then they are promted to choose a new option. I also chose for the player to forfit the game and die if they choose to flee. If a player chooses an invalid interger option they are promted to choose again. Inputing anything besides an interger will make my program crash so please please please please don't input anything besides an integer I have no idea how to make it not crash when inputing a non interger :,)

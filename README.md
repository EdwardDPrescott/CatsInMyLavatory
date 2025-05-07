# Summary

"Cats In My Lavatory" is a simple, text-based adventure game based on a ticking time bomb scenario. Imagine this: the game player needs to use the lavatory, but cannot because there are cats in the lavatory. The game is won if the game player can convince all the cats to exit the bathroom (before it's too late).


# Marketing Copy

When you gotta go, you gotta go! But what happens when your lavatory has been overrun with cats? There is not supposed to be cats in the lavatory, but there are! 'Please cats, won't you leave? Just a few minutes cats, please couldn't I be alone?' What will happen next? Will there be relief or tragedy?


# Product Management Summary

The goal is a casually entertaining, singe player game in a retro, throwback style. An entire game should take about 2-5 minutes. 

At the start of each turn of the game, the user is given a prompt, including: 
-	number of cats currently in the lavatory.
-	counter of turns elapsed.
-	Optional: A randomly chosen phrase; i.e., "Let's get a move on!"

Taking a turn:
The user enters an action, using either a letter or a keyword for each pre-defined action. Invalid actions yield an error message, a list of valid actions, and a chance to select again.
After an action is selected, a randomly determined outcome is chosen; the number of cats in the lavatory may be reduced, it may be unchanged, and it might actually increase. 

At the end of each turn, the game may have ended:
-	the player wins if zero cats are in the lavatory.
-	the player loses if too much time has passed, semi-randomly based on number of turns elapsed.


# Technical Design

(TBD: List of objects and descriptions of their interactions and responsibilities.)

The game will be authored in Python (version TBD).

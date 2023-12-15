# JFighter Battle Simulator
This is the project I made for my fall 2023 Advanced Java class I was in. It simulates two fighters in a battle with each other, and displays details of the battle.

# Overview
This Advanced Java project simulates two Fighters with the following stats:
* name
* health
* armor
* attack dice

These are all determined by the user.

They attack each other by rolling their dice (which are normal, six-sided dice)
then adding half of their current health to the sum of their dice rolls, called the health bonus.
They continue fighting until one Fighter loses all their health.

After each round, a description of how much damage
each Fighter generated and how much damage the Fighter took is displayed, in
addition to both Fighters' stats.

When the game is over, which occurs after either Fighter loses all their health,
a brief summary of how much health and armor each Fighter had after every round is displayed.

# Additional Details
To prevent never-ending battles, the program automatically deducts 1 point
from the Fighter's armor if they take damage during a round. This way, at least
one Fighter will eventually start taking real damage instead of having their
armor always absorb all of it.

There are two Forms in this program. One Form allows the player to input each
Fighter's stats, and the other Form is where the battle takes place.

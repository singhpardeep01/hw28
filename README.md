# hw28
Ye Olde Role Playing Game
1. Implement class Warrior as follows:
Attributes:
name
life/health/HP as an int
strength as an int
defense as an int
attack rating as a double
Methods:
constructor
takes String input to name the Warrior
initializes all attributes (eg, 125, 100, 40, 0.4)
isAlive
returns boolean indicating living or dead
getDefense
returns value of defense attribute
getName
returns value of name attribute
lowerHP
takes an int parameter, decreases life attribute by that amount
attack
takes a Monster as a parameter
calculates damage using this formula: damage = (strength * attack rating) - monster defense
damage should be an integer value
specialize
prepares the Warrior to perform a special attack
decreases defense attribute
increases attack attribute
normalize
prepares the Warrior to perform a normal attack
resets defense attribute
resets attack attribute
2. Implement class Monster as follows:
Attributes:
life/health/HP as an int
strength as an int
defense as an int
attack rating as a double
Methods:
constructor
initializes all attributes
sets strength to a random number ( ...Might I suggest the range [20,65) )
suggested other attribute values:
life: 150
defense: 20
attack: 1
isAlive
returns boolean indicating living or dead
getDefense
returns value of defense attribute
getName
returns value of name attribute
lowerHP
takes an int parameter, decreases life attribute by that amount
attack
takes a Warrior as a parameter
calculates damage using this formula: damage = (strength * attack rating) - warrior defense
damage should be an integer value
3. Include appropriate heading and comments. Remove all non-.java files from your YoRPG directory, then compress the directory and upload to the homework server.

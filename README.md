# What was this game for?

this game was made for the ASCII BASIC GAME 10Liner game jam hosted by Loudscotsbloke on itch.io

as the Jam name implies, the game must be written in BASIC, specifically interpreted basic, within 10 lines and using ASCII/PETSCII.

# Jam rules:

(Note: the rules are taken directly from the itch.io page https://itch.io/jam/ascii-basic-10liner)

The game must be written in BASIC (interpreted, not compiled)

10 Lines of code only

Abbreviations are allowed

No more than 72 characters per line

No Sprites or UDG's

Built in ROM ASCII/PETSCII (or equivilent) characters only

Sound/Effects are allowed

Bloxels are allowed as long as they come from the rom character set 

Each submission needs to come with an accompanying set of documentation that describes the game, the code and the story line. Please also include why you chose the system you 

did.. was it your first computer? Do you just like the platform? Please do tell!

# Documentation(as required by rules)

(this section will be found in README.TXT in the itch.io release as well as Github.TXT)

Game description:

BASIC Clicker is a simple game replicating the feel of clicker games in 10 lines of BASIC. Pressing the Z key increments the points by the upgrades + 1, and pressing F1 trades 5 points for an upgrade, the UI being quite basic, with the name of the game at the top of the screen and the points and upgrades being below the name.

The code:

The first line prepares both the P and U variables(0 and 1 respectively), the next line gets the key input which is stored in K$, Line 3 goes to line 5 if F1 is pressed, line 4 skips line 5, line 6 goes to line 8 if Z was pressed, line 7 skips line 8, line 8 adds P with U, line 9 sets E as U-1, prints "BASIC CLICKER," and prints both P and E, line 10 goes back to line 2, line 1 is only needed once.

The Storyline:

When I think of Clicker games, I usually think of a game where you gain points, Spend points to get more points, and a basic game without a story. Including the limitations of the Jam, I was unable stuff a story in to a small space.

Why I Commodore BASIC:

It's quite simple, my PC does not like the VICE emulator, I'll try to get it to work to get the D64 Image and PRG included with the Itch.io release.

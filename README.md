# Project Name
MSCH-C220 Final Project

## Theme
I interpreted the theme thematically: The game is based around one button that regenerates the world around it when pressed.

## Game Play
Objective:

Follow the instruction in the start menu and press the button until you can't anymore!

Game-play instructions:

WASD or arrows to move, space to jump.

## What did you struggle with?
Struggles or surprises you encountered during the development of the game:

I had difficulty seting up the character controller in the first place; the physics didn't work corectly until I copied all of repository 4a (save .git adn readme.md) into the folder. I didn't realize until too late that the HEAD file (I think?) mixed up Github Desktop, and it puched to repo 4a (which I'm sure you've noticed this still is, just renamed).

## Implementation
Features:

Started from scratch

2 - Repository has 10 commits (the first commit, my brainstorming below, was lost in the repository mix-up, but is visible at https://github.com/JoeNathan255/Project-07-old)

1 - Descriptive README.md

2 - There is gameplay (platforming and pushing fun buttons!)

2 - There is art (all levels, menus, and sprite sheets were drawn for this project)

0/2 - There is NOT sound (I'm quite thoroughly out of time)

2 - There is animation (detailed below)

2 - There are menus (in-world start and end screens, because I thought "If the game's already about pushing buttons, why not have the character push the start button?")

2 - There is a Level In Which The Gameplay Happens (7 iterations on a level)

?/5 - Specific focus on art and animation ⬎

## Special Focus
What is your special focus? What did you do for it? How would you rate your own effort? 1-5. (I will agree or disagree with this sentiment, but I want to know what you thought)

My special focus was animation: I drew sprite sheets in GIMP for the player (12 states, 17 unique frames), the button (2 states & frames), the dithering level transition (8 frames), and the animated background (3 frames).
I wanted the player to feel over-the-top bouncy for visual interest. In order to incorporate the anticipation, follow through, and squash and stretch I wanted, I based the player's state machine on 7 booleans and triggers, and it ended up pretty sophisticated (It also took up almost half my time on the project) and required exposing & creating variables in the player.cs script. I think the project as a whole (being made in a day) is rough around the edges, but I would call this part a 4, I think.

## References
2D character controller by Sebastian Lague: https://github.com/SebLague/2DPlatformer-Tutorial

# Created by
Jonathan Staten

# Brainstorming
Theme: One Button

mechanical (one-button games)
- one-button rhythm game
- - composition is slow (reuse earlier song of mine?)
  - requires precise tuning & inventive, simple gameplay (not just DDR or ADOFAI)
  - music & sound design main concern
- stunt car driver (à la MOTO X3M)
- - simple gameplay concept
  - requires custom and careful level design
  - physics more complicated (use sphere with custom accereration stuff as car like a drift racer?)

thematic (one button in/inspiring the game)
- button at the end of a level, changes level each time pressed
- - manageable scope
  - focus on art and juiciness?
  - - animation w/ state machine? I need to practice that
  - level design is a concern

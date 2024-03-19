 # Game Name

## Elevator Pitch

In Boolean Bonanza, you are presented with a grid of squares representing boolean values and operators (True, False, OR, AND, NOT, etc.). The player is able to move the rows and columns by clicking and dragging on a square, with the goal of making a row or column evaluate to True. If a row or column evaluates to True, it will be destroyed and give the player points. The goal is to make players able to evaluate boolean expressions on sight and understand how changes will affect their evaluation.

*A one sentence pitch for your game. Pretend that your were pitching your game to a executive going to the elevator. You have less than 60 Seconds. Check [this resource](http://www.gameacademy.com/perfecting-indie-games-elevator-pitch/) for more information.*

## Influences (Brief)

- Yoshi's Cookie:
  - Medium: Video Game
  - Explanation: Yoshi's Cookie multiplayer mode inspired the block movement of the grid. In Yoshi's Cookie, the player can move rows and columns such that their order is maintained and the blocks wrap around the other side. This will allow for greater control than a system like Candy Crush where only two blocks can be switched at a time.
- Candy Crush:
  - Medium: Video Game
  - Explanation: Candy Crush is a popular "match-3" style game that incorporates a pleasing visual style to draw in players. The graphics and animations of Candy Crush are considered so good as to be addictive by some, which could be mimicked to encourage players to participate in this educational game. Blocks in Candy Crush explode into satisfying particle effects when broken. This is something that should be incorporated into Boolean Bonanza.
- 2048:
  - Medium: Video Game
  - Explanation: 2048 is a popular online matching game where players are tasked with combining squares based on their numerical value. Squares start with low powers of 2 (2, 4, 8, etc.) and are combined with squares of the same value until the player reaches a square of number 2048. The difficulty comes from squares of different values getting in the way of making matches. This is similar to the difficulty in Boolean Bonanza, which comes from the fact that randomly ordered squares will evaluate to false or an error and thus not break.

## Core Gameplay Mechanics (Brief)

*Give a very high-level description of any core gameplay mechanics*

- Players are presented with a grid of squares representing boolean values and operators.
- Players can click and drag rows or columns on the grid of blocks to rearrange them.
- When a row (left to right) or a column (top to bottom) of boolean blocks evaluates to True, it will break and give the player points.
- After blocks break, the blocks above them will fall down until they are supported from below, with new blocks being spawned on the top of the grid.
- A timer will be displayed to let the player know how much more time they have in the current level before it ends.

# Learning Aspects

## Learning Domains

*Briefly list any and all of the disciplines and learning domains for this subject.*
Logic
Discrete Math
Introductory Programming (language is irrelevant given it has boolean values)

## Target Audiences

*Who are your learners?*
Boolean Bonanza is targeted for young computer scientists in middle school or high school looking to learn the basics of boolean statements.

## Target Contexts

*Describe what kinds of formal and informal learning contexts this will be used in (e.g., courses, k-12 computer labs during free time).*
Boolean Bonanza can be used at home as a study tool in order to practice boolean concepts. It can also be used in a classroom setting as an exercise to further strengthen one's booolean knowledge.

## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

-  Truthiness of Booleans: By the end of the lesson, players will be able to explain the truthiness of a boolean expression with at least two variables
-  Adjustment of Booleans: By the end of the lesson, players will be able to rearrange boolean expressions in order to achieve a truthful outcome.

- *Short Name*: *Formal Learning Objective #1*
- *Short Name*: *Formal Learning Objective #2*
- *Short Name*: *Formal Learning Objective #3*

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- Prior to the game, players need to be able to define the concept of evaluating a boolean expression.
- Prior to the game, players need to be able to evaluate a boolean expression.
- Prior to the game, players need to be able to evaluate a boolean expression with more than two variables.
- Prior to the game, players need to be able to define the concept of order of operations regarding boolean expressions.

## Assessment Measures

*Describe how the learning will be assessed, e.g., pre/post multiple-choice test, or SAT, or some other instrument.*

*If proposing a new instrument, briefly and concisely list some example assessment questions.*

A short pre-test and matching post-test should be designed to assess student learning.
The exact format of the test will be multiple choice where the student will be tasked with identifying which boolean expression of the four options provided evaluates to true. Students will be assessed based on their accuracy and efficiency.

- Given the following boolean expression, determine whether it evaluates to True, False, or an Error: True AND False OR NOT True (False)
- Given the following boolean expression, determine whether it evaluates to True, False, or an Error: False OR True AND True (True)
- Given the following boolean expression, determine whether it evaluates to True, False, or an Error: True AND True OR AND FALSE (Error)

# What sets this project apart?

*Give some reasons why this game is not like every other game out there. Whether the learning objective is unique, the gameplay mechanics are new, or what. You should persuade the reader that your game is novel and worthy of development. Consider arguments that would be persuasive to a Venture Capitalist, Teacher, or Researcher. These might be focused on learning needs, too.*

- Most computer science games revolve around code-writing, this one focuses solely on sharpening the players understanding of boolean expressions.
- The visuals of the game will mimic a Nintendo/Indie game with a bright and attractive atmosphere.
- With all input involving the shifting of blocks, the controls of the game are simple and easy to learn.
- The simple nature of the game along with its flashiness will be addictive to players.
- Players will improve their speed at evaluating boolean expressions as they improve at the game.

# Player Interaction Patterns and Modes

## Player Interaction Pattern

Players will use a mouse or touchscreen to press buttons and drag blocks across the screen. Players will engage with the game by themselves or competitively. One player at a time will actively play the game while trying to achieve a high score in the time allotted. After that player is finished, other players can use the same device to attempt to reach a new high score. In this way, players can compete and try to achieve their own personal high score or a score higher than their friends.

## Player Modes

*Your game has one or more player modes. Describe each discrete mode, considering things like menus too. Generally describe the transitions between modes too.*

- Main Menu: allows the player to pick between a 3 x 3 and 5 x 5 depending on the player's experience.
- 3 x 3 Boolean Grid: the player will make valid boolean statements with only one operator. After completing this level they will be given the option to play again or move on to the next level.
- 5 x 5 Boolean Grid: the player will make valid boolean statements with two operators. After completing this level they will be given the opportunity to play again.

# Gameplay Objectives
  
- Scoring Points By Making Valid Truthiness Statements:
    - Description: Each valid truthiness statement will result in gaining an amount of points adding to you current score.
    - Alignment: By gaining points, this will allow the player to see how many valid statements they are able to make.
- Scoring As Many Points As You Can Before The Time Is Up:
    - Description: In Boolean Bonanza there will be a time limit for each level. During this time the player must make as many valid        
      statements as they can. 
    - Alignment: Each time the player plays the game they will be able to see their learning progress each time they score higher given the       same time restriction.

# Procedures/Actions

During menu screens such as the main menu, the player will be able to move the mouse cursor and click on buttons to enter the game or change settings. On the gameplay screen, the player will use the mouse cursor to drag blocks across the screen. Clicking and holding down the mouse button on a block of the grid will allow the player to drag that block up, down, left, or right. The other blocks in that same row or column (depending on the direction of dragging) will also move to follow that block while wrapping around the edges of the screen. This allows the player to rearrange the blocks on the grid while still providing a challenge to plan moves in advance.
*Describe the control scheme and what actions a user can take in the game.*

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

# Objects/Entities

*What other things are in the world that you need to design? These may or may not directly translate to actual objects and classes.*

## Core Gameplay Mechanics (Detailed)

- *Core Gameplay Mechanic #1*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #2*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #3*: *Describe in 2 paragraphs or less, along with how it generally works*

    
## Feedback

*Explicitly describe what visual/audio/animation indicators there are that give players feedback on their progress towards their gameplay objectives (and ideally the learning objectives).*

*Describe what longer-term feedback you detect and give that guides the player in their learning and lets them know how they are doing in regards to the learning objectives.*

# Story and Gameplay

## Presentation of Rules

*Briefly describe how the player will learn the gameplay mechanics. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching mechanics iteratively and slowly.*

## Presentation of Content

*Briefly describe how the player will be taught the core material they are meant to learn. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching material iteratively and slowly.*

## Story (Brief)

*The Summary or TL;DR version of below*

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

# Assets Needed

## Aethestics

*Give a sense of the aesthetics of your game, the spirit and atmosphere. Use descriptive, evocative words that can help the reader understand the emotional response of your game.*

## Graphical

- Boolean Blocks
 - <img src="https://github.com/ACTrexler/CISC473_EGDD/blob/main/True.png?raw=true" alt="True Block" width="200"/>
 - <img src="https://github.com/ACTrexler/CISC473_EGDD/blob/main/False.png?raw=true" alt="False Block" width="200"/>
 - <img src="https://github.com/ACTrexler/CISC473_EGDD/blob/main/And.png?raw=true" alt="And Block" width="200"/>
 - <img src="https://github.com/ACTrexler/CISC473_EGDD/blob/main/Or.png?raw=true" alt="Or Block" width="200"/>
 - <img src="https://github.com/ACTrexler/CISC473_EGDD/blob/main/Not.png?raw=true" alt="Not Block" width="200"/>
- Textures:
  - *Texture 1*
  - *Texture 2*
  - *...*
- Environment Art/Textures:
  - <img src="https://github.com/ACTrexler/CISC473_EGDD/blob/main/ExampleBackplate.png?raw=true" alt="Example Backplate" width="300"/>
  - *Environment Texture 2*
  - *...*


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - Main Menu Music: [Puzzle Menu by caret7](https://opengameart.org/content/puzzle-menu), [Menu by tcarisland](https://opengameart.org/content/menu-1)
  - Gameplay Music: [Contemplation by bart](https://opengameart.org/content/contemplation), [Contemplation II by bart](https://opengameart.org/content/contemplation-ii)
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - Button Press: [8bit Menu Highlight by Fupi](https://opengameart.org/content/8bit-menu-highlight), [Clock Click by Mobeyee Sounds](https://opengameart.org/content/cloud-click)
  - Block Breaking: [Cork by Blender Foundation](https://opengameart.org/content/cork), [Breaking/Falling/Hit SFX by rubberduck](https://opengameart.org/content/75-cc0-breaking-falling-hit-sfx)


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3

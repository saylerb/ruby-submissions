Complete this form and the README.md before the first check in. Delete this line from your version.

# Game Time Check In # 1

## Basics

### Team
- [Robbie Jaeger](https://github.com/robbiejaeger)
- [Brian Sayler](https://github.com/saylerb)

### Game Name

Capture the Flag (Working Name)

### Give a Basic Description of the Game

Players try to capture a flag and return it to their home base to score points.

### Include a Link to or Screen Shot of the Game

[TagPro](http://i.imgur.com/vh5mjA1.png)

### Link to the Github repository for the project

[game-time repo](https://github.com/saylerb/game-time)

## The Plan

### Describe Your goals for the finished product

- Main Menu
  - create new game (or join existing game if sockets)
  - player can select timed game with rounds, or first to 10 points

- Movement
  - player can move around the screen using arrow keys (or WASD)  
  - player can move diagonally (press multiple keys)
  - player movement has realistic physics, arrrow keys accelerate 
  - ball-to-ball colisions are realistic

- Items and Obstacles
  - items: player can pickup powerups to increase speed and invulnerability
  - obstacles: spikes (instant death), barriers

- Multiplayer
  - node server allows people to join an existing game
  - 2-4 players can join a game and play simulaneously

- Scoring
  - player captures flag in enemy base and returns flag to home base to score points
  - scoring a point returns the captured flag to its base
  - rounds are timed to 5 minutes, or first to 10 points
  - a scoreboard at bottom of the screen indicates current score

- Tagging
  - when player has the flag, opposing players can tag that player,
  - tagging player returns the flag to its base
  - player dies and respawns at home base when they get tagged

- Levels
  - there are a couple maps to choose from (2 or 3)

### What is your MVP, or 'this was harder than I thought' plan?

- Main Menu
  - create new game (or join existing game if sockets)
  - player can select timed game with rounds, or first to 10 points

- Movement
  - player can move around the screen using arrow keys (or WASD)  
  - player can only move one axis at a time (no diagonal, cannot press mulitple directional keys at once) 
  - player moves at constant rate, acceration is instant
  - colisions stop players instantly

- Obstacles
  - obstacles: spikes only (instant death)

- Multiplayer
  - 2 players can play using arrow keys and WASD 

- Scoring
  - player captures flag in enemy base and returns flag to home base to score points
  - scoring a point returns the captured flag to its base
  - game is first to ~10 points
  - a scoreboard at bottom of the screen indicates current score

- Tagging
  - when player has the flag, opposing players can tag that player,
  - tagging player returns the flag to its base
  - player doesn't die, just loses flag

- Levels
  - there is a single maps to choose from


### What have you accomplished so far?

### Questions, Comments, Concerns?
- Keeping track of score across sessions (instances of name)
  - Client side without server
  - server side if using sockets
- How to incorporate 'increase in difficulty'
  - randomize flag 
  - randomize appearance of spikes/mines

- Creating maps, what can we use for sprites/map graphics?
  - where to find assets
  - animations for death/


-----

# Instructor Feedback Section

### Points for first check in (base 50)

* 50: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has completed some wireframing and/or written code.
* 40: First check in form and README was completed and pull requested in. Team has a well documented plan for moving forward with their game. Team has not written any code or created any wireframe documents.
* 25: First check in form completed but shows little effort at documenting/planning and team has not written any code.
* 0: First check in form was not completed.

### Instructor's Goals for Next Check In

* Goal 1: _eg. Create snake head constructor that draws itself on the canvas_

* Goal 2: _eg. Stop snake from moving past the boundry of the canvas when moving - write tests_

* Goal 3: _eg. Configure jshint and .jshintrc_

_Note: Instructor/Groups can add additional goals beyond 3. Grading for the next check in will be based on completion of goals_

### Stretch Goals

* _ie. Goals that are not required to meet the checkin, but would be good to have. Completion may result in extra credit points_

### Feedback?

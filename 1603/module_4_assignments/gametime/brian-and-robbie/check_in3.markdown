Complete this Form before the third check in. Delete this line from your version.

# Game Time Check In # 3

## Instructor Goal Completion

### GOAL 1

- Goal: Implement flag and ability for player to capture flag

![Blue ball captures red flag](http://g.recordit.co/kLXFJce85f.gif)

- Did you deviate from the instructions? No.
- Questions, Comments, Concerns?
  - lots of if statments!

### GOAL 2

-  Goal: Implement ball-ball collisions and acceleration 

![Gif of two balls touching](http://g.recordit.co/Fwks5tPzgR.gif)

- Did you deviate from the instructions?
  - No.
- Questions, Comments, Concerns?
  - acceleration can slow down sometimes, depending on what 
    monitor we're driving?

### GOAL 3

- Goal: Implement 'scoreboard' 

- Did you deviate from the instructions?
  - No
- Questions, Comments, Concerns?
  - simple scoreboard is good
  - still no way to end the game

### GOAL 4

- Goal:  Can tag/kill flag holders

![Gif of blue ball tagging red ball](http://recordit.co/Ix0D2pO1aJ/gif/notify)

![Gif of ball hitting spikes](http://g.recordit.co/8HaSZzuVsG.gif)

 Did you deviate from the instructions?
  - YES: We also implemented a basic system for spikes (beyond expectations)
    which is similar to the tagging system, (with or without
   flag) with additional feature: the player respawns at original location
- Questions, Comments, Concerns?
   - would like to implement some animation indicating tag/spike pop

## Next Steps?

- What do you feel the next steps should be?

- canvas layering might increase game performance (don't have to 
  re-draw the background every frame)
- we need to setup some end-game flow

### General Questions, Comments, Concerns?

- Probably passing on doing anything with websockets at this point
  - set up for basic sockets server was a pain, had to run 3 different servers
    to have it work with es6 and sockets
   - (nodemon to run express/node server and webpack --watch to build)
   - webpack-dev-server for building tests
  - realised it was probably not worth it to attempt to pivot to websockets

- Is passing many dependencies around an okay thing to do?
- We probably have many things that could be refactored
- Lots of collision dectection calculations for each 
  type of collision (wall, player, flag, spike...) maybe we should
  have a master collisions class? Some way to optimize that.

-----

# Instructor Section

### Points for Second Check In (base 50)

* 60 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way. Students completed additional stretch goals.
* 50 points: Students documented their work well and completed all base goals or have documented where/why they deviated from the goal in a reasonable way.
* 35 points: Students completed all base goals but did not document the work appropriately in their form || did not complete 1 goal and failed to document why in a reasonable way.
* 25 points: Students did not complete more than 1 goal.
* 0 points: Students did not complete check in form prior to eval.

### Instructor's Goals for Next Check In

These goals should center around wrapping up the game:

 - Matching the [rubric](https://github.com/turingschool/lesson_plans/blob/master/ruby_04-apis_and_scalability/gametime_project.markdown) requirements
 - Refactoring/Cleaning up test coverage
 - Making the game compelling for players
 - Making sure the README and other documentation is up to snuff
 - Making sure the game is deployed

_Note: Instructor/Groups can add additional goals beyond 3. Grading for the next check in will be based on completion of goals_

### Feedback?

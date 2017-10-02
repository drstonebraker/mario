# Mario vs Browser

A remake of a [Super Mario World bonus game](https://youtu.be/7a8JmQ_ds4A) in HTML5 canvas.


## Learning Goals

+ Create a javascript application using object oriented design.
+ Implement basic gravity, physics, and collision detection systems.
+ Utilize HTML5 canvas instead of a DOM to render application state.
+ Utilize the Web Audio API


## Functionality

+ Player will have movement, including jumping and falling, which mimics the physical behavior of the original game.
+ Player will be able to freezes the items in the rotating item boxes by jumping into them.
+ Once Player has frozen all boxes, Player will be awarded green mushrooms based on how many items matched 3-in-a-row.
+ Game will have music and sound effects, which can be toggled on or off.
+ A help menu displaying game controls and objectives can be toggled on or off.


# Display

+ The playable area of the game will consist of an HTML5 canvas element in the center of the screen, with the rest of the viewport being filled by a blue-and-white striped background based on the original game.
+ The will be toggle control buttons displayed in the top-right of the viewport for music, sound effects, and game instructions.


## Implementation

Mario vs Browser will utilize the Matter.js javascript physics engine for handling gravity, movement, and object interaction.


## Timeline

#### Day 1:
+ Install and configure webpack
+ Upload all sprites to cloudinary
+ Learn basic Matter.js API
+ Render sprites onto viewport
+ Set up initial features of gravity system

#### Day 2:
+ Implement item animation within item boxes
+ Implement character movement and animation -- left, right, up, down, and jumping.

#### Day 3:
+ Establish collision detection and player/item box interaction
+ Begin implementing item box animation

#### Day 4:
+ Finish item box animation
+ Award 1-up mushrooms
+ Implement control toggles

#### Day 5:
+ Implement sounds & music

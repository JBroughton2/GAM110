# GAM110
I'm uploading my work towards GAM110 here because I like to use proper version control and can't access James' repository.
Values I'm using for everything to work:

## Player
Max Speed = 2
Balloons Left = 5
Game Over UI= The game over screen UI in the canvas ( just makes the screen dark and stops the game)

## Level Generator
(do what ever you want play around with this to make a good amount of obstacles)
step 1: Drag all the obstacles you want into the drop down array called Obstacles
Number of OBstacles = 70 
Level Width: 10
Min Y = 3
Max Y = 8

## Main Camera
Has the player dragged into the player slot
speed = 0.125
offset = X:0, Y:2, Z:-10

## Balloons
They all have a box collider on them and are attached to the player
P Control : this is the player controller script dragged in from the player object
Player is the player object
Pop Blowback doesn't workd becasue I'm stupid and Unity doesn't like me.

## Notes

all that's kinda needed is a score counter to go up while the player is alive and UI. Feel free to add stuff as you like.

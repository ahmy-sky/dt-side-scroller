# DT-SIDE-SCROLLER

This week we are going to continue our exploration of gaming by creating a side-scroller. We will be working on this game for a few sessions to cover a number of different fundamental coding concepts.

As before our game uses a simple infinite loop (created using the `requestAnimationFrame` function on the window) to update the positions of everything on the screen based on the previous state and user inputs.

However the game is pretty boring in its current state. Niether the spaceship nor the projectiles it shoots have basic collision detection, and enemies all spawn from the same location at a predictable interval. Let's make it better!

We need to add some basic, elegant game logic to allow our spaceship to interact with its environment. Some suggestions on what to try are listed below.

## INSTRUCTIONS

The basic game loop has been set up for you to create the following:

1. A spaceship which can be controlled fom the keyboard: W - up; S - down; A - left ; D - right; SPACEBAR - shoot.
2. Enemies which spawn every two seconds and move across the screen.

The project is built inline within `index.html`, simply open this file in a browser to preview the project.

## GOALS

You should feel free to adapt the game as you see fit but some ideas:

1. Implement collision detection so that enemies are destroyed if a projectile hits them;
2. Add collision detection so that the spaceship is destroyed if it collides with an enemy;
3. Cause enemies to spawn at random positions and at random intervals on the screen;
4. Add background graphics that continually scroll to the left; and
5. Add game state in the form of a scoreboard, lives for the spaceship and a gameover dialogue. 


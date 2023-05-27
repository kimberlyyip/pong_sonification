# pong_sonification
Created by Kimberly Yip and Zev Goldhaber-Gordon.

A musical recreation of the classic video game Pong in the program Max. A project for MUSIC.208 at Carleton College. 

## Overview
Created in Max, this project recreates the classic video game Pong with different musical parameters controlled by various aspects of the game.
One of the paddles is controlled by OSC output sent from a phone with the Gyrosc app. This allows a user to play pong against the computer.
Each paddle determines the pitch of its own sine tone based on the y-position with low pitches representing a y-position near the top of the screen and high pitches representing a y-position near the bottom of the screen.
The ball also controls a sine tone that has an overlaying bitcrusher effect. Similar to the paddles, the y-position of the ball determines the pitch of the tone. The x-position of the ball controls the panning of the sound.
A unique sound is played when the ball hits the paddle which is supplied by the imported sound files. Each paddle has a unique sound associated with it.
A video of the maxpatch in action can be seen below. 


https://github.com/kimberlyyip/pong_sonification/assets/113480089/c1f91e89-7b04-4e7e-83de-a93904f6a0c4




## Artist Statement
Zev was inspired to do this project for the randomization project earlier this term but decided to use it for the instrument assignment instead, and Kimberly was excited about the idea as well. 
This musical recreation of the classic arcade game Pong in Max is meant to be fun to play along with and interesting to hear. 
We started by figuring out many of the gameplay controls, including how to get one paddle to be controlled by a phone gyroscope and the other to follow the ball naively, and getting the ball to bounce cleanly. 
Once we had a mostly functional pong prototype, we started adding musical components so that we could cleanly set the position and velocity of the ball and paddles to different outputs without worrying about how it affected the controls. 
A changing tone comes from the ball and each paddle based on how high on the screen they are, with each paddle’s noise coming from their respective ear, and the ball’s noise panning from left to right depending on where it is on the screen. 
In addition, the ball has a bitcrusher effect applied to it and the paddles make video game-y noises when the ball hits them, in order to give the whole patch an arcade-y feel. 
One piece of gameplay that was tricky to implement was “ball english,” which is when the ball’s y velocity changes when it hits a paddle, depending on where on the paddle it hit. 
We felt that this was an important part of the original pong rules, and also that it changes up the pitches being played in interesting ways each time the ball goes back and forth. 
For contributions, Kimberly designed the moving bars and display features, along with setting up the gyroscope input, combining the intermediate patches, implementing the bitcrusher sonification, and doing the cleanup. 
Zev set up the game rules, ball velocity/bouncing/paddle collision and scoring, implemented english, and wrote the artist statement.

## Future Directions
In the future, it would be nice to modify the patch such that it an accomadate two players. This should be easily accomplished by connecting another device with the Gyrosc app to the patch. 
It would also be interesting if we included a background track or beat that accompanies the gameplay to produce a more cohesive musical piece.


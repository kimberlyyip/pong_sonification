# pong_sonification
Created by Kimberly Yip and Zev Goldhaber-Gordon.

A musical recreation of the classic video game Pong in the program Max. A project for MUSIC.208 at Carleton College. 

## Artist Statement
Zev was inspired to do this project for the randomization project earlier this term but decided to use it for the instrument assignment instead, and Kimberly was excited about the idea as well. 
This musical recreation of the classic arcade game Pong in Max is meant to be fun to play along with and interesting to hear. We started by figuring out many of the gameplay controls, including how to get one paddle to be controlled by a phone gyroscope and the other to follow the ball naively, and getting the ball to bounce cleanly. 
Once we had a mostly functional pong prototype, we started adding musical components so that we could cleanly set the position and velocity of the ball and paddles to different outputs without worrying about how it affected the controls. 
A changing tone comes from the ball and each paddle based on how high on the screen they are, with each paddle’s noise coming from their respective ear, and the ball’s noise panning from left to right depending on where it is on the screen. 
In addition, the ball has a bitcrusher effect applied to it and the paddles make video game-y noises when the ball hits them, in order to give the whole patch an arcade-y feel. 
One piece of gameplay that was tricky to implement was “ball english,” which is when the ball’s y velocity changes when it hits a paddle, depending on where on the paddle it hit. 
We felt that this was an important part of the original pong rules, and also that it changes up the pitches being played in interesting ways each time the ball goes back and forth. 
For contributions, Kimberly designed the moving bars and display features, along with setting up the gyroscope input, combining the intermediate patches, implementing the bitcrusher sonification, and doing the cleanup. 
Zev set up the game rules, ball velocity/bouncing/paddle collision and scoring, implemented english, and wrote the artist statement.

# 50033-gamedev-lab1
Unity project for Lab 1 Checkoff

### Checkoff Status
Gameplay can be seen [here](https://www.youtube.com/watch?v=a0xx62jm3as). Try to get to a score of 25!

I finished all the checkoff components with some minor changes on my end, such as rewriting the enemy controller which was bugging out and optimizing the UI component tree for easier handling. 

The reset mechanic was implemented by calling a public method on the relevant GameObjects which returns them to their original states (instead of SceneManager since I wanted to have the possibility of keeping track of deaths across restarts).

### Competition Submission
The extra stuff I implemented was mainly to push this lab towards a game-like state where people would enjoy playing it for a couple minutes or so. I took inspiration from the hit indie game "This War of Mine" which offers a similarly tense atmosphere and obscuring vision mechanics during scavenging.


#### List of extra features:
* Custom RigidBody2D physics manipulation for better Mario-like jumping
* Singleton AudioManager instance to handle music/SFX
* Character animation with event-driven SFX (unfortunately I only found out later this overlaps with lab 2)
* Usage of Universal Render Pipeline for lighting and future work on shadow/ray casting
* Creation of gameplay mechanics like increasing goomba speed and music volume/pitch manipulation based on score, gruesome death messages

Never touched Unity/C# before so I may not exactly use best practices, however further labs should reflect my learning.

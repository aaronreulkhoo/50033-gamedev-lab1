# 50033-gamedev-lab2
Unity project for Lab 2 Checkoff

### Checkoff Status
Gameplay can be seen [here](https://www.youtube.com/watch?v=cd40X-ZmdTA).

Implemented everything necessary for the lab checkoff with a few minor improvements:
* Moved to boxcasting instead of collision events for ground checking(less layers + objects to manage, yay!)
* Converted SpringJoint2D box hitting mechanism to collision angle checking + animation event (better performance and no more sagging blocks)
* Created master block prefab with options to easily make interactive or normal blocks


#### List of extra features (some carried over):
* Singleton AudioManager instance to handle music/SFX
* Used Coroutines to implement classic invisible blocks
* Played around with URP shadow casters

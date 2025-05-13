# MatthewGallionCapstone
## Drive Link to Demo Download (Performance on Lower End Computers is not Guaranteed)
(https://drive.google.com/drive/folders/1dXmoffQM3AfX2CUIChEJfRBuHUIzTlVZ?usp=sharing)
Controls use a controller, but there's keyboard functionality for everything except diving

## Project Description
The goal of “Is Your Microwave Running?” Is to create a fast paced, 3D platformer that is reasonably challenging and replayable.  For the purposes of the Capstone Project, my goal is to create a playable demo of some capacity.

## Current Progress and What's Left (As of Milestone 3)
As of Milestone 3 I've created a basic player model, rigged the skeleton, weighted the skin, created animations in the Unreal sequencer, and applied them in actual gameplay using a state machine.  This technically wasn't necessary to have a functional final product for the Capstone Project, but I felt that having some level of visual polish would make my game much more presentable, and having the placeholder capsule I was using sliding around with no animations wasn't going to make that cut.  The remaining work I have now is finishing the last of the player movement (most likely just adding the ability to do a dive and wall jumps), and creating a demo level.  On paper creating a level would probably be the more difficult of the two, but because I spent time in Milestone 2 creating repurposable obstacle Blueprints, that should help to expedite the process.

## Progress As of Demo
The game currently has three stages, each with a 90 second timer (timer UI broke, so it's currently not visible).  Each stage has an end that loads the player into the next stage.  The player has the ability to run, jump, dive, and wall jump; All of these actions have animations controlled using a state machine.  There are obstacles such as moving platforms, jump pads, and spinning hammers.  If the player falls off the map or gets hit by a hammer, they respawn at the start of the current level without resetting the timer.  There are no lives, rather a "Game Over" is reached by running out of time in a stage.  This is about as much progress I expected to make for this project, but if I could add more I'd fix the timer UI to properly show up, fine tune how the movement feels, and create some sort of hub world for the player to load into stages (level groups) from.

## Milestones
### Milestone 1
(https://drive.google.com/file/d/1DRkZytHuh8bDVOjWrwJ_dnB-PjPTqZ3_/view?usp=sharing)

### Milestone 2
(https://drive.google.com/file/d/1y9-F0HiKmOVioCfVoaYS_abP3bCDjYdJ/view?usp=sharing)

### Milestone 3
(https://drive.google.com/file/d/1AgNHnM0tvZt9H0K8maUTWqK6oqRGA0Zc/view?usp=sharing)

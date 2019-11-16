# E11b-First-Person

The goal of this repository is to create the beginning of a first person shooter using a kinematic body with a camera that can interact with a scene.

* We build the scene, then create a kinematic body for the character.
* We then create two collision shapes for it (body and feet). The feet are there to simulate "walking" a little better, rather than gliding over everything.
* We add a spatial node with a camera and then a mesh weapon.
* We add a script to the Kinematic body that will:
  - handle each key press (input...which way is the player trying to go?)
  - handle mouse motion (controlling the camera while limiting its movement)
  - physics (gravity, velocity, speed, movement)

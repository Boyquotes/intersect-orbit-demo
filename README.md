# intersect-orbit-demo
Demo for Godot 3.2.3 showing how to intersect an object in an orbit by calculating the trajectory using binary search

Some notes:
- The planet's local position is at (0, 0) and it moves because it's rotated around its offset.
- The spaceship can fly through the star.
- The calculated trajectory gets more inaccurate when the planet is further from the ship.
- You can probably do this with an equation as well but I couldn't solve the equation.

# FlockingBehavior :bird: 

This is an implementation of [flocking behavior](https://en.wikipedia.org/wiki/Flocking_(behavior)) in Unity. Inspiration was drawn heavily from *The Nature of Code* by Daniel Shiffman.

Bin-lattice spatial subdivision is used to improve performance; my computer can easily handle flocks of ~200 boids (bird-thingies) at 200 FPS. The `FlockingBehavior` has numerous properties to drive boid motivations and behavior.


![Input](/flocking.gif?raw=true)

## TODO

1. Add paths for boids to follow when the target is out of sight.
2. Add option to check adjacent bins/cells when boids check for neighbors.
    - Would improve flock appearance (reduce lines when clumping), but may negatively impact performance.

# License

MIT.

Hopefully someone out there on the interwebs can use this in a game they're developing, especially since I can never seem to finish one :sweat_smile:

If you do, I'd love to hear about it!

# How it works
## Physics
- Spear conected with PinJoint2D to Dwarf [RigidBody2D](https://docs.godotengine.org/en/stable/classes/class_rigidbody2d.html) Node (this is for physical connection)
- Spear also connected to "hand"-bones with [RemoteTransform2D](https://docs.godotengine.org/en/stable/classes/class_remotetransform2d.html) Nodes
- Inverse Kinematic from [u/Ephemeralen](https://www.reddit.com/user/Ephemeralen) to make arms follow spear and hands.

![als text](doc/physics.png)

## Sprite deformation
Followed [this tutorial](https://docs.godotengine.org/en/stable/tutorials/animation/2d_skeletons.html)

![als text](doc/uv.png)

# Assets
## Dwarf Image
[Dwarf Image Source](https://marketplace.roll20.net/browse/set/559/15-dwarves)
![alt text](assets/max.png)

## Goblin Image
[Goblin Image Source](https://marketplace.roll20.net/browse/set/544/02-goblins-and-kobolds)
![alt text](assets/goblin.png)

## Combat map
[Combat map Source](https://www.pinterest.de/pin/308215168254181967)
![alt text](assets/gso9pxdx8ik31.png)

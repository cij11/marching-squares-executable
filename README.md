# marching-squares-executable
Executable demo of 2d deformation project with using marching squares algorithm

This demo uses the marching squares algorithm to transform an array of topographical data into a mesh that can be rendered and collided with.
It represents physical bodies using an internal marching squares grid, and an external convex hull. Smaller bodies interact with the concave inner geometries of larger bodies, and the convex outer hulls of bodies they are a similar size to.

Controls
WSAD - Move the player up, down, left, right when close to a body
WSAD - Move the player forwards and backwards, or rotate the player counterclockwise and clockwise when in space.
Space - Dig.
Shift - Dig a large area. May be slow on portable devices.

IKJL - Apply an upwards force, a downwards force, or a counterclockwise or clockwise moment to the body the player has boarded. This allows the player to 'pilot' the object they are standing on, if it is small enough.

Mousewheel up/down - Zoom.
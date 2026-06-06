# Pygame Updater

2D game development library for pygame.

## Features

- Physics
- Collision detection
- A* Pathfinding
- Jump Point Search
- Flow Field Navigation
- Tilemaps
- Animation System

## Installation

pip install pygame-updater

## Example

from pygame_updater.physics.physics import PhysicsForces

physics = PhysicsForces()

velocity = [0, 0]
physics.gravity(velocity)
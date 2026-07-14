# Pepse 2D Game

A Java-based 2D platform game developed using object-oriented design principles.

## Overview

Pepse is a side-scrolling 2D game featuring a dynamic world,
player movement, procedural terrain generation, and interactive objects.

## Features

- Object-oriented game architecture
- Dynamic world generation and loading
- Procedural terrain generation using noise functions
- Player avatar with:
  - Movement and jumping mechanics
  - Animation states
  - Energy management system
- Day/night cycle
- Dynamic clouds and weather effects
- Collision detection and object interaction
- Trees, fruits, and environmental objects

## Technologies

- Java
- Object-Oriented Programming
- DanoGameLab Framework
- Git

## Architecture

The project is divided into independent modules:

- `Avatar` - player controller, movement, animation, energy system
- `Terrain` - procedural terrain generation
- `WorldManager` - dynamic loading and removal of world objects
- `Flora` - tree and vegetation generation
- Factories for reusable game object creation


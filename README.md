# zombies-oh-no
A bite-sized intro to Unity3d

## Goals:
1. This mini game will introduce you to just enough concepts to be able to build a simple game on your own!
2. You will be taught just enough to research new concepts and ideas on your own to implement in your game.

## What will you build?
You will be building a prototype that includes all the game mechanics for a zombie chaser game.

This includes:
1. Learning about the Unity3d editor interface
1. Laying down primitive objects
1. Learning about Rigidbodies and Collisions
1. Adding a script to make your player object move with an input device.
1. Learning about Unity3d's smart navigation system - navmesh baking and navmesh agents.

## Play-By-Play Instructions
1. Create a new Unity3d project
1. Create a quad and lay it flat to be used as a floor.
1. Create a sphere, set it's tag to 'Player'.  Put a color on it if you want.
1. Put a Rigidbody Component on the sphere so that it doesn't fall through the floor.
1. Create another sphere.  It will be an enemy. Put Rigidbody components on them all so they can collide into obstacles.
1. Create some simple obstacles between you and the enemy.
1. Select your floor and all obstacles together, make sure to check the 'Static' box.
1. Bake all your obstacles and floor so that it creates a navmesh - the floor should turn blue.
1. Create a component on all your enemies and configure target to be the 'Player'.
1. Customize as you wish using asset store!

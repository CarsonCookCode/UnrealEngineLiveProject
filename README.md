# Unreal Engine Live Project - Code Summary
## Introduction
I worked in an Agile/Scrum environment to build a game in Unreal Engine using C++ and blueprints. I created a puzzle escape game in a dungeon setting from a first person perspective and a 3d environement using the assets at my disposal. We used Azure DevOps to manage our repositories and user stories. I developed a productive workflow after familiarizing myself with the tools at my disposal. Over the two week sprint I had many opportunities to learn what it means to work as part of a team on a single project.

Here are some of the highlights from the project:


## Story 1: Creating the Basic Scenes

For my first user story I needed to set up the basic scenes. I set up the SceneLoader and then using TileMaps set up the first level with the sprites that I found.

![DigDugStart](https://user-images.githubusercontent.com/73494842/149604794-feac0f79-4069-4a73-8d78-d65fc7a78a27.png)

## Story 2: Level Design and Player Behavior
Once I had set the scene I set up DigDug's basic movement.

![DigDugMovement](https://user-images.githubusercontent.com/73494842/149605094-22ff0632-197b-4744-a252-f062725e5209.png)

I also built digging ability which enable the character interaction with the TileMap. When DigDug digs, he slows down as well as clears the path to the enemy.

![DigDugDigging](https://user-images.githubusercontent.com/73494842/149605541-b7415fd2-361b-4e9c-a2dd-bc7b07dea22e.png)

## Story 3: Opposition Behavior
Next, I built the AI for the enemies using A* pathfinding. As well as creating the rest of the opposition behavior.

![DigDugOpposition](https://user-images.githubusercontent.com/73494842/149605777-13a40f46-e1e2-453a-9971-61caf27180e0.png)


## Story 4: Complete Gameplay Model
Here I finished the game in its basic form. I added the inflation mechanic when DigDug shoots the enemy. Also added animations to DigDug and the enemies.

![DigDugInflation](https://user-images.githubusercontent.com/73494842/149606229-e662d752-aade-4e30-b240-1a30555bed51.gif)

![DigDugInflationCode](https://user-images.githubusercontent.com/73494842/149606432-8e722a67-dc38-4f0d-a8a4-df0b6d8d0299.png)


## Story 5: Final Touches
I made some final touches to my game, including sound effects and music.

![DigDugFinal](https://user-images.githubusercontent.com/73494842/149606755-74503d66-3451-43ec-b8c8-855d347fdc58.gif)


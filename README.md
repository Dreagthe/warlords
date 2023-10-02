# warlords
my first roguelike


Overview

This project is a roguelike game built using the tcod library. Players can navigate a procedurally generated dungeon, interact with entities, and engage in turn-based gameplay.
Features

    Procedural Dungeon Generation: The game generates unique dungeons every time you play.
    Entity System: Define and manage players, enemies, and other entities in the game.
    Game Actions: Players can perform various actions like moving, attacking, and more.
    Tile-based Graphics: The game uses a tileset for rendering entities and the game world.

File Structure

    main.py: The main game loop and entry point.
    actions.py: Defines the game actions and their effects.
    engine.py: Manages the game loop, rendering, and state updates.
    entity.py: Defines the Entity class representing game objects.
    game_map.py: Handles the game map generation and interactions.
    input_handlers.py: Translates user inputs into game actions.
    procgen.py: Responsible for procedural generation of rooms and dungeons.
    tile_types.py: Defines various tile types for the game.
    requirements.txt: Lists the project dependencies.

Dependencies

    tcod: A popular library for creating roguelike games.
    numpy: Used for numerical operations and array manipulations.

To install the dependencies, run:

pip install -r requirements.txt

Getting Started

    Clone the repository.
    Install the dependencies using the command above.
    Run main.py to start the game.

Controls

[Provide a list of game controls or refer to the in-game help.]
Credits

[Credit any sources, inspirations, or assets used in the game.]

Feel free to contribute and extend the game. Enjoy playing!
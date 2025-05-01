MadronaMPGeo is an auxiliary data set for the MadronaMPEnv project. MapdronaMPEnv is an experimental learning environment for training AI agents to play competitive multiplayer games with reinforcement learning. This environment is part of an ongoing research collaboration between Activision and the Graphics Lab at Stanford University. Currently, the codebase is an active work in progress; we plan to provide plug-and-play setup instructions in a future update.

This environment is built on top of the [Madrona Engine](https://madrona-engine.github.io), a prototype game engine for building high-performance learning environments that can execute at millions of frames per second by parallelizing gameplay logic on the GPU.

The data in data/enviroment.usd includes simplified versions of two Call of Duty® multiplayer maps containing collision data, spawn points and the navigation mesh.

Map 1:

![Map 1](data/map_1.png)

Map 2:

![Map 2](data/map_2.png)

Both of them are stand-alone maps, but also can be found as sections in the Call of Duty®: Warzone™ map [Caldera](https://github.com/Activision/caldera). The scene files live in data/environments.usd which can be imported in most third-party applications, or inspected in script using the [OpenUSD](https://openusd.org/release/index.html) Python [bindings](https://pypi.org/project/usd-core/).

The first map (red) can be found in the map_docks section of Caldera while the second map (green) can be found in the map_beachhead district. 

![alt text](data/in_caldera_context.png)

Copyright © 2025 Activision Publishing, Inc.

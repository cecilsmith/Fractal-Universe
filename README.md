# Fractal-Universe

Largely based on [Sebastian Lague](https://github.com/SebLague)'s work. 
  * [Procedural Planets](https://github.com/SebLague/Procedural-Planets)
  * [Spherical-Gravity](https://github.com/SebLague/Spherical-Gravity)

This Unity project creates a procedurally generated world that a player can explore. The world uses heightmaps to assign color (which is also blended) to give the illusion of oceans, beaches, and mountains. This is by no means a finished product--it is merely a proof of concept. 

<img width="374" alt="Screen Shot 2022-07-16 at 11 05 01 PM" src="https://user-images.githubusercontent.com/19243227/179383901-f0036596-5d0a-489f-8322-f44133509733.png">

<img width="910" alt="Screen Shot 2022-07-16 at 11 11 02 PM" src="https://user-images.githubusercontent.com/19243227/179383910-845fee25-4c41-4b84-91e3-98b27df5c27f.png">


### Current issues:
* There needs to be a LOD (level of detail) system to optimize generation. Currently, the whole world is being rendered at once which is expensive in terms of processing. This proposed system would only render parts of the world that are visible to the player. Additionally, the areas of the world that are closest to the player would be rendered in higher detail, thus giving the illusion that the whole world is rendered in high detail without the same performance impact.
* There is nothing for the player to do other than walk around a blank, colorful planet.
* Biomes (forests, deserts, rivers, etc.)

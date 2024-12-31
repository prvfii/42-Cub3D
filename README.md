𝑪𝒖𝒃𝟑𝑫
     
      A 3D game engine inspired by Wolfenstein 3D, using raycasting.

________________________________________________________________________________

Description

Cub3D is a project from the 42 School curriculum. It involves creating a 3D game engine using a 2D map representation and rendering a first-person perspective with raycasting. The project emphasizes understanding graphics programming, working with the minilibx graphics library, and handling events like player movement and interactions.

Features

	•	3D rendering using a raycasting algorithm.
	•	Player movement in a first-person perspective.
	•	Wall collision detection to prevent passing through walls.
	•	Dynamic lighting effects (optional).
	•	Customizable maps defined in a .cub file format.
	•	Textured walls and floors/ceilings (optional solid colors).
	•	Event handling for keyboard inputs (movement, rotation, etc.).

 Requirements

	•	Graphics Library: minilibx.
	•	Compiler: gcc.
	•	OS: macOS.

 Controls

	•	W/A/S/D: Move forward, left, backward, and right.
	•	Left/Right Arrows: Rotate the player’s view.
	•	ESC: Exit the game.

 Map Format

The game requires a .cub file as input, which defines the map and game configuration. The map must follow these rules:

	1.	The map must be closed/surrounded by walls (1).
	2.	Valid characters:
	•	0: Walkable space.
	•	1: Wall.
	•	N/S/E/W: Player starting position and orientation.
	3.	The .cub file must include:
	•	Texture paths for walls (NO, SO, WE, EA).
	•	Floor (F) and ceiling (C) colors in RGB format.

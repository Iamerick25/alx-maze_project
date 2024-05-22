# 3D_Maze
![maze gif](https://user-images.githubusercontent.com/88714347/171422634-8adc8811-2559-4ba1-967f-4caf909c3f22.gif)
- The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!.
- The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- It runs on Mac OS X and Linux/Ubuntu. The game uses the technique raycasting to create the apparent 3D nature of the maze.
# About SDL2
- Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games. for more information on [SDL2](https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer)

# Requirements to Play
  - Linux/ubuntu or Macos
  - SDL2 and its sdl_image

# Play the game
 - clone the [github repository](https://github.com/Iamerick25/alx-maze_project.git)
 - Compile all .c files in the maze directory:
  ```
  gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm $(sdl2-config --cflags --libs) -lSDL2_image -o maze
   ```
 - Execute ./maze and play game.
 - Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
 - Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

# Controls
 W or up arrow key - Moving forward
 S or down arrow - Moving backward
 left arrow key - to rotate the player in counter clock wise direction
 right arrow key - to rotate the player in clock wise direction

# Author
- Erick Chinyem Onwochei(https://github.com/Iamerick25)

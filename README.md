Creating a 3D maze with raycasting

How to Compile and Run
SDL2 and SDL2_image are required to compile and use this program
Compile with the following flags: gcc -O2 -g -Wall -Werror -Wextra -pedantic -I code/header code/*.c -lSDL2 -lSDL2_image -lm -o maze `sdl2-config --cflags --libs` 
Run the file : ./maze no_tex


To-Do
Adding textures
Enemies / obstacles / objects


Controls
Uu key : move forward
Down key : move backward
Left key : strafe left
Right key : strafe right
Q : rotate camera left
D : rotate camera right
F : toggle fullscreen
ESC : quit

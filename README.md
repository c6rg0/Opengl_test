# README

This is a small glfw/opengl learning project.
Nothing here is original, just making sense of graphics and c++.

If you want to run the exe, you have to go to terminal, go to the /Opengl_test directory, and then run the main.exe.

That probably won't work since I haven't linked the the libraries to the exe, and you don't have downloaded the necessary libraries installed, you will have to work that part out yourself, you need to install opengl and glfw libraries (although glfw header files are included in the project).

To recompile the code:
$ g++ src/main.cpp -Iinclude -o main.exe -L/mingw64/lib -lglfw3 - lopengl32 -lgdi32

Oh yeah, you need to install gcc/g++ too, good luck...

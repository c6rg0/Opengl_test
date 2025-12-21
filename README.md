# README

This is a small glfw/opengl learning project.
Nothing here is original, just making sense of graphics and c++.

To compile the project:
(have nix installed)
- nix-shell (this will install all dependencies)
- g++ src/main.cpp src/glad.c -Iinclude -o main $(pkg-config --cflags --libs glfw3)


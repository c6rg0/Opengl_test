# README
> This is a small glfw/opengl learning repo.
> Nothing here is original.

- To compile the project (have nix installed):
`$ nix-shell`
`$ g++ src/main.cpp src/glad.c -Iinclude -o build/window $(pkg-config --cflags --libs glfw3)`


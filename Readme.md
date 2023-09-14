# Simple example С project with cmake
> Ensure you have *cmake* and *make* installed on your machine

## Quick start

- Run `cmake -S ./src -B ./build` to build project (using CMakeLists.txt file in src directory)
- Run `make -C build && ./build/cooll` to build and run program from src/main.c file
- Run `make -C build install` to install your program as globally available binary command. After that, you will be able to run the cooll command anywhere in your terminal.
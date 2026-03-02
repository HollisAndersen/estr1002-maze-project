cmake_minimum_required(VERSION 3.16)
project(maze_game C)

set(CMAKE_C_STANDARD 23)

add_executable(maze_game main.c
        globals.c
        globals.h
        maze.c
        maze.h
        ui.c
        ui.h)

target_link_libraries(maze_game ncursesw)

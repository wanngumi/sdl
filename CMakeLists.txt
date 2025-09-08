cmake_minimum_required(VERSION 4.0.0)

project(sdl)

add_executable(sdl main.cpp)
target_link_libraries(sdl SDL3)

add_executable(arch arch.c)

add_executable(snake snake.c)
target_link_libraries(snake SDL3)

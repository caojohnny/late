cmake_minimum_required(VERSION 3.7.2)
project(late C)

set(CMAKE_C_STANDARD 99)

add_executable(late main.c)

# Compiler options
set(CMAKE_C_FLAGS "-Wall -Wextra -Werror -O0 -ansi -pedantic -lxcb")

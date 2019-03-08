cmake_minimum_required(VERSION 2.8)
project(hello C)

set(CMAKE_C_STANDARD 11)

add_executable(hello hello.c say.c)
cmake_minimum_required(VERSION 2.8)
project(hello C)

set(CMAKE_C_STANDARD 11)
SET(SRC_LIST hello.c)

add_executable(hello ${SRC_LIST})
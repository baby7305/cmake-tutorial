cmake_minimum_required(VERSION 2.8)
project(hello C)

set(CMAKE_C_STANDARD 11)

ADD_LIBRARY(libhello say.c)
add_executable(hello hello.c)

SET_TARGET_PROPERTIES(libhello PROPERTIES OUTPUT_NAME "hello")
TARGET_LINK_LIBRARIES(hello libhello)
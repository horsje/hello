cmake_minimum_required(VERSION 3.6)
project(hello)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

set(SOURCE_FILES main.c)
add_executable(hello ${SOURCE_FILES})
cmake_minimum_required(VERSION 3.6)
project(es2)
set(CMAKE_C_STANDARD 99)


set(SOURCE_FILES main.c)
add_definitions(-mavx)
add_executable(es2 ${SOURCE_FILES})
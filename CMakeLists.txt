cmake_minimum_required(VERSION 3.0.0)
project(clox C)

file(GLOB_RECURSE SOURCES "src/*.c")

add_executable(clox ${SOURCES})

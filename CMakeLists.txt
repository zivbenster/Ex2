cmake_minimum_required(VERSION 3.2)
project(Ex2)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

set(SOURCE_FILES MyString.c MyString.h)
add_executable(Ex2 ${SOURCE_FILES} Main.c LineSeparator.h LineSeparator.c)
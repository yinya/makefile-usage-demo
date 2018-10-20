cmake_minimum_required(VERSION 3.12)
project(demo_01 C)

set(CMAKE_C_STANDARD 99)

add_library(demo_01 library.c library.h)
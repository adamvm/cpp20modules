cmake_minimum_required(VERSION 3.11)
project(cpp20modules)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -pedantic -Wextra")

add_executable(modules  main.cpp)

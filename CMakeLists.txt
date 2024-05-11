cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 20)

project(DSAPLAYGROUND)

add_library(array ./src/Array/array.cpp ./src/Array/array.h)

add_executable(dsa ./src/main.cpp)

target_link_libraries(dsa array)

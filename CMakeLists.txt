cmake_minimum_required(VERSION 3.5)
project(arcc)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp)
add_executable(arcc ${SOURCE_FILES})
cmake_minimum_required(VERSION 3.30)
project(learn_cpp)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)
include_directories(src)

add_executable(learn_cpp
        src/main.cpp
)
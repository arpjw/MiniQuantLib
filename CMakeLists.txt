cmake_minimum_required(VERSION 3.10)
project(MiniQuantLib)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(include)

add_executable(MiniQuantLib tests/test_main.cpp)

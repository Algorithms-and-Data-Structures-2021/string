cmake_minimum_required(VERSION 3.15 FATAL_ERROR)

project(string_classwork)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# add executables
add_executable(app main.cpp src/string.cpp)
target_include_directories(app PUBLIC include)
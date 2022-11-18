
cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_COMPILER "/usr/bin/g++")
# set the project name

project(tarea4
VERSION 1.0
LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(tarea4 main.cpp)
target_include_directories(tarea4 PUBLIC ${PROJECT_SOURCE_DIR}/include)



# add the executable
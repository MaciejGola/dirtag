cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)

project("dirtag")

add_subdirectory(src)

add_executable ("${PROJECT_NAME}" src/main.cpp)

cmake_minimum_required(VERSION 3.10)


project(Project VERSION 1.0)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "../bin/")
# set(CMAKE_LIBRARY_OUTPUT_DIRECTORY "../lib/")

set(CMAKE_CXX_STANDARD 11)


# --------------------------------------------
include_directories(include)

add_executable(hello-world ./src/hello_world.cpp)

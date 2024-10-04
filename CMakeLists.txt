cmake_minimum_required(VERSION 3.30.4)
project(
    lesson4
    VERSION 1.1
    DESCRIPTION "First project"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# set(CMAKE_BUILD_TYPE DEBUG)
add_executable(lesson4)
# add_library(lesson4)
set(sources
main.cpp)

target_sources(lesson4 PRIVATE ${sources})
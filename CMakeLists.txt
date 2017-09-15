cmake_minimum_required (VERSION 3.0)
project(reliable C CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED on)

include_directories(${CMAKE_CURRENT_LIST_DIR})

add_library(reliable "reliable.c" "reliable.h")
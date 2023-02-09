cmake_minimum_required(VERSION 3.24)
project(vigenere-breaker)

set(CMAKE_CXX_STANDARD 17)

include_directories(src)

file(GLOB_RECURSE main-sources "src/*.cpp")

add_executable(vigenere-breaker src/main.cpp ${main-sources})

cmake_minimum_required(VERSION 3.20)
project(khf5)

set(CMAKE_CXX_STANDARD 20)

file(GLOB SOURCES "*pp")

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror -Wall -Wextra -pedantic")

add_executable(hf1 ${SOURCES})
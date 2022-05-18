cmake_minimum_required(VERSION 3.20)
project(xproc)

find_package(Boost REQUIRED system )

set(CMAKE_CXX_STANDARD 20)

include_directories(include )

add_subdirectory(test)

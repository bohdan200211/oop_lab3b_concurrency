cmake_minimum_required(VERSION 3.17)
project(oop_lab3b_concurrency)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(extern/doctest)
add_subdirectory(extern/libfort)

add_subdirectory(extern/SFML)


add_subdirectory(include)
add_subdirectory(src)
add_subdirectory(tests)
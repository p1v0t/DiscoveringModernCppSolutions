cmake_minimum_required(VERSION 3.14)

project(DiscoveringModernCppSolutions
    DESCRIPTION "My solutions for exercises in the book: \"Discovering Modern C++: An Intensive Course for Scientists, Engineers, and Programmers\""
    HOMEPAGE_URL https://github.com/p1v0t/DiscoveringModernCppSolutions
    LANGUAGES CXX)

option(BUILD_EXERCISE_4.8.3 "Ex 4.8.3 requires external libs to build" OFF) 

add_subdirectory(ch1)
add_subdirectory(ch2)
add_subdirectory(ch3)
add_subdirectory(ch4)
add_subdirectory(ch5)

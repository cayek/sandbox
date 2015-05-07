cmake_minimum_required (VERSION 2.6)

project(sandbox)

#include dir
include_directories("src/")


add_executable(HelloWord  src/main.cpp src/HelloWord.h src/HelloWord.cpp )

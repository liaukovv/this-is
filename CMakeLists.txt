cmake_minimum_required(VERSION 2.6)

project(this-is)

add_executable(this-is main.cpp)

install(TARGETS this-is DESTINATION bin)
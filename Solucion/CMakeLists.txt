cmake_minimum_required(VERSION 3.10)

project(pointer_function)

file(GLOB SOURCES "src/*")

add_executable(pointer_function ${SOURCES})

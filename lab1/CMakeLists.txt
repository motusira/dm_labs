cmake_minimum_required(VERSION 3.30)

project(lab1 C)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

set(SOURCES src/main.c)

add_executable(${PROJECT_NAME} ${SOURCES})

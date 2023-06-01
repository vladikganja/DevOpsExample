cmake_minimum_required(VERSION 3.15)

project(devopsExample CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

SET(SRCS main.cpp)

add_executable(${PROJECT_NAME} ${SRCS})

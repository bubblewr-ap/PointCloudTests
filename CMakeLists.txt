cmake_minimum_required(VERSION 3.0)

project(pointcloudtests)

add_executable(pointcloudtests main.cpp)

install(TARGETS pointcloudtests RUNTIME DESTINATION bin)

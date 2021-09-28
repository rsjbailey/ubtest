cmake_minimum_required(VERSION 3.20)
project(hellolipo VERSION 1.0 LANGUAGES CXX)
add_executable(hello main.cpp)

install(TARGETS hello)

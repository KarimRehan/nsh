cmake_minimum_required(VERSION 3.10)
project(nsh)
add_executable(myprog src/builtins.cpp src/executer.cpp src/main.cpp src/parser.cpp)
target_include_directories(myprog PRIVATE include)

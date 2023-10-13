cmake_minimum_required(VERSION 3.20)

project(BolyaiPontszam VERSION 1.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} /FC")  # full path in error messages


add_executable(BolyaiPontszam main.cpp)

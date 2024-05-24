cmake_minimum_required(VERSION 3.28)
project(Cplus_portfolio)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Cplus_portfolio
        snake.cpp
        snake.h)

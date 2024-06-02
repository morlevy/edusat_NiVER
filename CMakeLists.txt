cmake_minimum_required(VERSION 3.21)
project(edusat_NiVER)

set(CMAKE_CXX_STANDARD 14)

include_directories(edusat)

add_executable(edusat_NiVER
        edusat/edusat.cpp
        edusat/edusat.h
        edusat/options.cpp
        edusat/options.h)

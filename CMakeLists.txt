cmake_minimum_required(VERSION 3.20)
project(lab3)

set(CMAKE_CXX_STANDARD 20)


configure_file(input.txt input.txt COPYONLY)

add_executable(lab3_1 main.cpp Car.h Vector.h
        main.cpp)

add_executable(lab3_2 mainn.cpp Car.h Vector.h
        main.cpp)
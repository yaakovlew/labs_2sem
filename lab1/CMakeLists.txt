
cmake_minimum_required(VERSION 3.17)
project(lab1 C)

set(CMAKE_C_STANDARD 99)

add_executable(lab1 main.c tests.h actionvector.h actionvector.c)
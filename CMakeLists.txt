cmake_minimum_required(VERSION 3.29)
project(Praktikum2 C)

set(CMAKE_C_STANDARD 90)

add_executable(Praktikum2 main.c
        zahlen.h
        zahlen.c)

target_compile_options(${PROJECT_NAME} PRIVATE -std=c89 -Werror -Wall -Wextra -pedantic -Wconversion)
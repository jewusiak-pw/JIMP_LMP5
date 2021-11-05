cmake_minimum_required(VERSION 3.19)
project(JIMP_LMP5 C)

set(CMAKE_C_STANDARD 99)

add_executable(JIMP_LMP5 test.c q_sort.c q_sort.h insort.c insort.h)
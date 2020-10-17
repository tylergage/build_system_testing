cmake_minimum_required(VERSION 3.18)
project(test_proj)
add_executable(myapp main.c)
install(TARGETS myapp DESTINATION bin)

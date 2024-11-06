cmake_minimum_required(VERSION 3.0)
project(Add)

add_library(add tests/add.cpp)
add_executable(main tests/main.cpp)
target_link_libraries(main add)
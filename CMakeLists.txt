cmake_minimum_required(VERSION 3.7)
project(b)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
link_directories("/Users/raoshaoquan/CLionProjects/b/lib")
add_executable(b ${SOURCE_FILES})
target_link_libraries(b c)
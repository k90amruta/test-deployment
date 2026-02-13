cmake_minimum_required(VERSION 3.16)
project(myapp)

set(CMAKE_CXX_STANDARD 17)

add_executable(myapp src/main.cpp)

enable_testing()
add_subdirectory(tests)
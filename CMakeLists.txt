cmake_minimum_required (VERSION 3.0)
enable_language(C)

project(romz-gdbm)

include(CTest)
enable_testing(true)

# SET( CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=c++11")

add_subdirectory(3rdparty/googletest)
add_subdirectory(src)
add_subdirectory(tests)

add_subdirectory(examples/ex01)

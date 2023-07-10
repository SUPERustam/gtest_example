cmake_minimum_required(VERSION 3.22)
project(gtestProject)

find_package(GTest REQUIRED)
include_directories(${GTEST_INCLUDE_DIRS})

add_executable(runApp sample1.cpp)
target_link_libraries(runApp ${GTEST_LIBRARIES} pthread)
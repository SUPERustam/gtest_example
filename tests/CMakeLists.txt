cmake_minimum_required(VERSION 3.22)
project(gtestProjectTesting)

find_package(GTest REQUIRED)
include_directories(${GTEST_INCLUDE_DIRS})

add_executable(runTests sample1_unittest.cpp ../sample1.h ../sample1.cpp)
target_link_libraries(runTests ${GTEST_LIBRARIES} pthread)
enable_testing() # for ctest and to add new test configurations in this CMakeLists.txt

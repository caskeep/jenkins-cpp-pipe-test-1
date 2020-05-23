cmake_minimum_required(VERSION 3.1)
project(run)
add_executable(run main.cpp)
set_target_properties(run PROPERTIES RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/bin")
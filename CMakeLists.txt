cmake_minimum_required(VERSION 3.1.4)
project(mlp VERSION 1.0.0 LANGUAGES C CXX)
set(CMAKE_CXX_STANDARD 17)

add_subdirectory(matrix)

add_library(mlp multilayerPerceptron.cpp)
target_compile_options(mlp PUBLIC -O3 --std=c++17)
target_link_libraries(mlp PUBLIC matrix)

target_include_directories (mlp PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
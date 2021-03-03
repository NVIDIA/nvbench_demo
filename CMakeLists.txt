# 3.18.3 fixed bugs in MSVC + CUDA + C++17 support
cmake_minimum_required(VERSION 3.18.3)

project(NVBenchDemo CUDA)

add_subdirectory(nvbench)

add_executable(example_bench example_bench.cu)
target_link_libraries(example_bench nvbench::main)

cmake_minimum_required(VERSION 3.26)
project (cpp-project-template)

find_package(fmt CONFIG REQUIRED)

add_executable(main "src/main.cpp")
target_link_libraries(main PRIVATE fmt::fmt)

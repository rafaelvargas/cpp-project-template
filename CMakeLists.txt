cmake_minimum_required(VERSION 3.26)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

project(cpp-project-template)

find_package(fmt CONFIG REQUIRED)

add_executable(main "src/main.cpp")
target_link_libraries(main PRIVATE fmt::fmt)

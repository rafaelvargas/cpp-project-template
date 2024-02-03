cmake_minimum_required(VERSION 3.26)
project (cpp-project-template)

# set(VCPKG_ROOT "vcpkg")
# set(CMAKE_TOOLCHAIN_FILE "${VCPKG_ROOT}/scripts/buildsystems/vcpkg.cmake" CACHE STRING "")


# find_package(fmt CONFIG REQUIRED)
# find_package(CLI11 CONFIG REQUIRED)

file(GLOB SOURCES "src/*.cpp")

add_executable(main ${SOURCES} "src/main.cpp")
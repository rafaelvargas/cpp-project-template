
## C++ Project Template

Just a C++ project template. 

It uses [vcpkg](https://github.com/microsoft/vcpkg) for package management and [CMake](https://cmake.org/) as a build system.


## Building the project

1. Bootstrap vcpkg
    #### Unix
    ```bash
    ./vcpkg/bootstrap-vcpkg.sh
    ```
    #### Windows
    ```bash
    .\vcpkg\bootstrap-vcpkg.bat
    ```
2. Install dependencies and build
    ```bash
    cmake --preset=default
    cmake --build build
    ```

## Choosing a license

A license can be easily chosen in [here](https://choosealicense.com/).



https://github.com/isocpp/CppCoreGuidelines
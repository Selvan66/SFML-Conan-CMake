# SFML-Conan-CMake

This is a template that links SFML using CMake and Conan

## Requires

* CMake
* Conan

For Linux you will also need to install some libraries

## How to build

Debug:

```bash
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Debug ..
cmake --build .
```

## External

Template used `conan.cmake`: [https://github.com/conan-io/cmake-conan](https://github.com/conan-io/cmake-conan)

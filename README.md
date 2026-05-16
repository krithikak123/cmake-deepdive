# C++ Sample with CMake and Gradle

This sample shows a minimal C++ application built with both CMake and Gradle.

## Build with CMake

```powershell
cmake -S . -B build/cmake
cmake --build build/cmake --config Release
```

## Build with Gradle

```powershell
gradle build
```

## Notes

- The CMake build output directory is `build/cmake`.
- On Windows with a Visual Studio generator, the executable may appear in `build/cmake/Release`.
- The Gradle build delegates to CMake, so it produces the same binary.

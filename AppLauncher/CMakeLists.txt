# CMakeList.txt : CMake project for AppLauncher, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (AppLauncher "AppLauncher.cpp" "AppLauncher.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET AppLauncher PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.

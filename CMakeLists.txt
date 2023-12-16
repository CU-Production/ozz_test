cmake_minimum_required(VERSION 3.27)
project(ozz_test)

set(CMAKE_CXX_STANDARD 20)

# 3rd party libs
add_subdirectory(3rd_party)

# APPS
add_subdirectory(src/ozz_anim)
add_subdirectory(src/ozz_skin)

## imgui
add_library(imgui imgui/imgui.cpp imgui/imgui_draw.cpp imgui/imgui_tables.cpp imgui/imgui_widgets.cpp)
target_include_directories(imgui PUBLIC imgui)

## ozz-animation
add_library(ozzanim ozz/src/mesh.cc ozz/src/ozz_animation.cc ozz/src/ozz_base.cc)
target_include_directories(ozzanim PUBLIC ozz/include)

## sokol
add_library(sokol INTERFACE)
target_include_directories(sokol INTERFACE sokol)

## util
add_library(util INTERFACE)
target_include_directories(util INTERFACE util)

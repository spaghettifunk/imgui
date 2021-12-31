cmake_minimum_required(VERSION 3.3)
project(imgui)

add_library(imgui STATIC
  imgui_demo.cpp
  imgui_draw.cpp
  imgui_widgets.cpp
  imgui_tables.cpp
  imgui.cpp
)

target_include_directories(imgui PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})

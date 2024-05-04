cmake_minimum_required (VERSION 3.22)

add_executable (green-zone "main.cpp")

target_link_libraries (green-zone
    glfw
    libglew_static
)

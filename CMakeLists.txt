cmake_minimum_required (VERSION 3.22)

project (green-zone)

add_subdirectory (glfw)
add_subdirectory (glew)
add_subdirectory (src)

target_include_directories (green-zone PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/glfw/include)
target_include_directories (green-zone PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/glew/include)

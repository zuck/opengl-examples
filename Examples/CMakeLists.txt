include_directories(${CMAKE_CURRENT_SOURCE_DIR}/External)

file(COPY Content DESTINATION ${CMAKE_RUNTIME_OUTPUT_DIRECTORY})

add_subdirectory(Window)
add_subdirectory(Triangle)
add_subdirectory(BlinkColorTriangle)
add_subdirectory(TexturedQuad)
add_subdirectory(Transformations)
add_subdirectory(MirroredCube)

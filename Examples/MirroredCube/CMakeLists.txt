add_executable(MirroredCube WIN32 MACOSX_BUNDLE
    main.cpp
)

target_link_libraries(MirroredCube ${OPENGLEXAMPLES_REQUIRED_LIBS})

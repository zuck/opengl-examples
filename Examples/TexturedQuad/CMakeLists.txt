add_executable(TexturedQuad WIN32 MACOSX_BUNDLE
    main.cpp
)

target_link_libraries(TexturedQuad ${OPENGLEXAMPLES_REQUIRED_LIBS} png)

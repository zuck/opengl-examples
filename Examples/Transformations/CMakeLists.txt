add_executable(Transformations WIN32 MACOSX_BUNDLE
    main.cpp
)

target_link_libraries(Transformations ${OPENGLEXAMPLES_REQUIRED_LIBS} png)

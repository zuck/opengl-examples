add_executable(Triangle WIN32 MACOSX_BUNDLE
    main.cpp
)

target_link_libraries(Triangle ${OPENGLEXAMPLES_REQUIRED_LIBS})

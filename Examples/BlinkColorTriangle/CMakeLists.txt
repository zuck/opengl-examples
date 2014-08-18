add_executable(BlinkColorTriangle WIN32 MACOSX_BUNDLE
    main.cpp
)

target_link_libraries(BlinkColorTriangle ${OPENGLEXAMPLES_REQUIRED_LIBS})

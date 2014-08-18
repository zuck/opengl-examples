add_executable(Window WIN32 MACOSX_BUNDLE
    main.cpp
)

target_link_libraries(Window ${OPENGLEXAMPLES_REQUIRED_LIBS})

set(libname glad)

add_library(${libname}
    STATIC
        src/glad/glad.h
        src/glad/glad.c
)

target_include_directories(${libname}
    PUBLIC
        "${CMAKE_CURRENT_SOURCE_DIR}/src"
)

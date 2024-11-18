FILE(GLOB_RECURSE component_sources ${CMAKE_CURRENT_SOURCE_DIR}/src/*.*)

idf_component_register(SRCS ${component_sources}
                       INCLUDE_DIRS "src"
                       REQUIRES arduino)

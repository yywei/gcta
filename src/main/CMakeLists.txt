SET(CMAKE_INCLUDE_CURRENT_DIR ON)
file(GLOB SOURCES "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp")
add_library(mainV1 ${SOURCES})

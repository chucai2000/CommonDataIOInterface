set(PROJECT_NAME Utilities)
project(${PROJECT_NAME})

set(UTILITIES_HDR Utilities.h)
set(UTILITIES_SRC Utilities.cpp)

add_library(${PROJECT_NAME} 
            ${UTILITIES_HDR} ${UTILITIES_SRC})


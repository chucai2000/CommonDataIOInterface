set(PROJECT_NAME DataProcess)
project(${PROJECT_NAME})

set(DATA_IO_HDR DataIO.h)
set(DATA_IO_CPP DataIO.cpp DataProcess.cpp)

include_directories(${CMAKE_SOURCE_DIR}/Utilities)
include_directories(${CMAKE_CURRENT_SOURCE_DIR})
add_executable(${PROJECT_NAME} 
               ${DATA_IO_HDR} ${DATA_IO_CPP})


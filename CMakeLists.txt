cmake_minimum_required(VERSION 3.10.2)

project(IT003.M21.PMCL-Nhom14 VERSION 1.0.0)

set(PROJECT_SRC ${CMAKE_CURRENT_SOURCE_DIR}/src/main.cpp)

add_executable(IT003.M21.PMCL-Nhom14 WIN32 ${PROJECT_SRC})

add_subdirectory(libs/SFML)
target_link_libraries(IT003.M21.PMCL-Nhom14 PUBLIC sfml-graphics sfml-audio sfml-window sfml-system)
set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT IT003.M21.PMCL-Nhom14)
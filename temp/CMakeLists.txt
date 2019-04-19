include_directories(${PROJECT_SOURCE_DIR}/cal/include)

aux_source_directory(./src SRC_LIST)
add_executable(temp ${SRC_LIST})
target_link_libraries(temp cal)
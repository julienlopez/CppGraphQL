set(EXE_NAME demo_server)

file(GLOB_RECURSE SOURCE_FILES ./*)
add_executable(${EXE_NAME} ${SOURCE_FILES})

target_link_libraries(${EXE_NAME} CppGraphQL::LibServer)

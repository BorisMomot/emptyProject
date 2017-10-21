project(emptyProject)
cmake_minimum_required(VERSION 2.8)

#aux_source_directory(. SRC_LIST)

set(SRC_FILES_DUMMYPR main.cpp)
set(SRC_TEST_SRC test.cpp)

add_executable(${PROJECT_NAME} ${SRC_FILES_DUMMYPR})
add_executable(${PROJECT_NAME}_test ${SRC_TEST_SRC})

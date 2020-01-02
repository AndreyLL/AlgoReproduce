cmake_minimum_required(VERSION 3.5)
project(Studing LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

SET(CMAKE_LIBRARY_OUTPUT_DIRECTORY
    ${PROJECT_BINARY_DIR}/bin
    CACHE PATH
    "Sigle directory for all"
    )

SET (CMAKE_RUNTIME_OUTPUT_DIRECTORY
    ${PROJECT_BINARY_DIR}/bin
    CACHE PATH
    "Single directory for all")

SET (CMAKE_ARCHIVE_OUTPUT_DIRECTORY
    ${PROJECT_BINARY_DIR}/lib
    CACHE PATH
    "Single directory for all")

enable_testing()



add_subdirectory(src  build/src)
add_subdirectory(test build/test)


#add_executable(foo main.cpp)
#target_link_libraries(foo GTest::GTest GTest::Main)

#add_test(AllTestsInFoo foo)


#set(CMAKE_CXX_STANDARD 11)
#set(CMAKE_CXX_STANDARD_REQUIRED ON)

#add_executable(tests1 main.cpp)

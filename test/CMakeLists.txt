project(all_tests)

set(CMAKE_CXX_STANDARD 11)
set(Test_source main_test.cpp)
add_executable(all_tests ${Test_source})
target_link_libraries(all_tests)


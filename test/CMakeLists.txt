project(all_tests)

find_package(GTest REQUIRED)

set(Test_source main_test.cpp)
add_executable(all_tests ${Test_source})
target_link_libraries(all_tests)


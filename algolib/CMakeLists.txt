project(Algorithm)
set(ALGO_LIBRARY inc/algo.hpp
            src/algo.cpp)
add_library(Algorithm STATIC ${ALGO_LIBRARY})
target_include_directories(Algorithm PUBLIC /)

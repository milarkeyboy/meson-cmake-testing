project(bar CXX)

add_library(bar_lib src/bar.cpp)
target_include_directories(bar_lib PUBLIC include)

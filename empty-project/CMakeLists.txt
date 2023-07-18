add_executable(empty-project
    # Source files
    source/main.cpp

    # Header files
    include/example.hpp
)

target_include_directories(empty-project PRIVATE include)
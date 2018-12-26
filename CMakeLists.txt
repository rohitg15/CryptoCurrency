cmake_minimum_required(VERSION 3.4)
set (CMAKE_CXX_STANDARD 14)

project(cryptocurrency)

enable_testing()

add_subdirectory(blockchain)
add_subdirectory(client)

# add_subdirectory(test)
# Add other directories


set(blockchain_SRCS
    blockchain.h
    blockchain.cpp
)

# Declare the library
add_library(blockchain STATIC
    ${blockchain_SRCS}
)

# target_link_libraries(libsocket
#     libfoo
# )

# Specify here the include directories exported
# by this library
target_include_directories(blockchain PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}
)

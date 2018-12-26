set(Client_SRCS
    main.cpp
)

add_executable(client
    ${Client_SRCS}
)

# Specify here the libraries this program depends on
target_link_libraries(client
    blockchain
)

install(TARGETS client DESTINATION bin)

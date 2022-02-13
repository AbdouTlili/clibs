cmake_minimum_required(VERSION 3.0)

project(Hello)


set(SRCS
    main.c 
    hello.c
    )


set(HEADERS
    hello.h
    )

add_executable(hello ${SRCS} ${HEADERS})
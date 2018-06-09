CMAKE_MINIMUM_REQUIRED (VERSION 3.8)
PROJECT(server C)

SET (CMAKE_C_STANDARD 11)

INCLUDE_DIRECTORIES(server include)

ADD_EXECUTABLE (server
    include/config.h
    include/net.h
    include/error.h
    src/error.c
    src/net.c
    src/main.c)


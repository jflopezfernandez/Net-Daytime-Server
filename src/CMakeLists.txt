CMAKE_MINIMUM_REQUIRED (VERSION 3.8)
PROJECT(tbd C)

SET (CMAKE_C_STANDARD C11)

ADD_EXECUTABLE (tbd
    include/net.h
    include/error.h
    include/net.c
    include/error.c
    src/main.c
)


# Copyright 2020-present Yeolar

file(GLOB TFWRAPPER_BASE_SRCS *.cpp)
file(GLOB TFWRAPPER_BASE_HDRS *.h)

add_library(tfwrapper_base OBJECT ${TFWRAPPER_BASE_SRCS})

install(FILES ${TFWRAPPER_BASE_HDRS} DESTINATION ${CMAKE_INSTALL_INCLUDEDIR}/tfwrapper)

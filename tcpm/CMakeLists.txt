cmake_minimum_required (VERSION 2.8.11)

add_library(tcpm src/tcpm.c)

set(INC_CSDIR ${CMAKE_CURRENT_SOURCE_DIR})
target_include_directories (tcpm PUBLIC ${INC_CSDIR}/src/ ${INC_CSDIR}/include)


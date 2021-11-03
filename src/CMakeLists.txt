cmake_minimum_required (VERSION 3.8)
project (hello_world)

include_directories(
	${CMAKE_CURRENT_SOURCE_DIR}
)


if(CMAKE_COMPILER_IS_GNUCXX)
    SET(CMAKE_CXX_FLAGS "-g -O0 -fprofile-arcs -ftest-coverage")
    include(CodeCoverage)
endif()


FILE(hello_world_SRCS
	"src/main.cc"
)

add_executable (hello_world ${hello_world_SRCS})

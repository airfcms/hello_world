cmake_minimum_required (VERSION 3.8)
project (hello_world)

include_directories(
	${CMAKE_CURRENT_SOURCE_DIR}
)

add_executable (hello_world "src/main.cc")

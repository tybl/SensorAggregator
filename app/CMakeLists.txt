################################################################################
# License: The Unlicense (https://unlicense.org)
################################################################################

add_executable(collect)
target_link_libraries(collect PRIVATE
	compiler_settings
	Boost::system
	Threads::Threads)
target_sources(collect
	PRIVATE
	collect/main.cpp
	collect/server.cpp)

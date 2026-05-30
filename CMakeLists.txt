cmake_minimum_required(VERSION 3.13.4)

project(MyCoolMod LANGUAGES CXX)

find_package(geode REQUIRED)

add_geode_mod(
	    ${PROJECT_NAME}
	        GDMods

	                SOURCES
	                        main.cpp
	                        )
)

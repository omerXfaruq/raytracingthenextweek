cmake_minimum_required (VERSION 2.6) 
project (raytracingthenextweek) 

file(GLOB_RECURSE INCS "*.h")
file(GLOB_RECURSE CPPS "*.cpp")
file(GLOB_RECURSE CPPS "*.cc")

add_executable(raytracingthenextweek ${CPPS} ${INCS})


                                                                              
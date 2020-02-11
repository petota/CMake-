cmake_minimum_required(VERSION "3.7.1")

project("Dianita")

add_executable("${PROJECT_NAME}" "Main.cpp")
install(TARGETS "${PROJECT_NAME}" DESTINATION bin)
install(FILES "Main.cpp" DESTINATION src)
set(DCMAKE_SH="CMAKE_SH-NOTFOUND")
cmake_minimum_required(VERSION 3.27)
project(project_2__Gradebook_)

set(CMAKE_CXX_STANDARD 14)

include_directories("Project2##")

add_executable(project_2__Gradebook_
        "Project2##/course.cpp"
        "Project2##/course.h"
        "Project2##/Gradebook.cpp"
        "Project2##/Gradebook.h"
        "Project2##/main.cpp"
        "Project2##/student.cpp"
        "Project2##/student.h")

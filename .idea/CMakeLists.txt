cmake_minimum_required(VERSION 4.2)
project(_idea)

set(CMAKE_CXX_STANDARD 14)

add_executable(_idea
        .gitignore
        CLionProjects.iml
        editor.xml
        modules.xml
        vcs.xml
        workspace.xml
        ../Math/main.cpp
        ../Section11/Random/main.cpp
        ../Section11/CodingExercise22/main.cpp
        ../Section11/FunctionDefinitions/main.cpp
        ../Section11/FunctionPrototypes/main.cpp)

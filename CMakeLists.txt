cmake_minimum_required(VERSION 3.24)
project(SimpleFileManager)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_AUTOMOC ON)
set(CMAKE_AUTORCC ON)
set(CMAKE_AUTOUIC ON)
set(CMAKE_PREFIX_PATH $ENV{QT_CMAKE_PREFIX_PATH})

find_package(Qt6 COMPONENTS
        Core
        Gui
        Widgets
        REQUIRED)

add_executable(SimpleFileManager main.cpp)
target_link_libraries(SimpleFileManager
        Qt6::Core
        Qt6::Gui
        Qt6::Widgets
        )


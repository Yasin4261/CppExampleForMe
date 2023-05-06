cmake_minimum_required(VERSION 3.22)

project(MyProject)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# Kaynak dosyalarını belirtin
set(SOURCES
    main.cpp
    # Diğer kaynak dosyaları buraya eklenebilir
)

# İlk hedefi belirtin
add_executable(MyExecutable ${SOURCES})

IGSTK-5.2
=========

IGSTK-5.2 that works with VTK6.1 and QT5.2.1

In CMake set CMAKE_PREFIX_PATH to QT and enable IGSTK_USE_QT.

ex.

CMAKE_PREFIX_PATH:PATH=C:/Qt/Qt5.2.1/5.2.1/msvc2012_64_opengl
IGSTK_USE_QT:BOOL=ON
CMAKE_LIBRARY_PATH:PATH=C:/Program Files (x86)/Windows Kits/8.0/Lib/win8/um/x64

The core IGSTK library will build. Haven't had a chance to fix issues for igstkTests project.
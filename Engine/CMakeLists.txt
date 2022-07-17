# CMakeList.txt : projet CMake pour Simple_2DEngine, incluez la source et définissez
# la logique spécifique au projet ici.
#
cmake_minimum_required (VERSION 3.8)

# Ajoutez une source à l'exécutable de ce projet.
add_executable (Simple_2DEngine "Simple_2DEngine.cpp" "Simple_2DEngine.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Simple_2DEngine PROPERTY CXX_STANDARD 20)
endif()

# TODO: Ajoutez des tests et installez des cibles si nécessaire.

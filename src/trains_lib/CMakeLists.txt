add_library(trains_lib STATIC braid.cpp
edgevert.cpp
embedding.cpp
General.cpp
Graphalg.cpp
graph.cpp
Graphset.cpp
Graputil.cpp
help.cpp
hshoe.cpp
Matrix.cpp
ttt.cpp)

target_include_directories(trains_lib PUBLIC ${CMAKE_CURRENT_LIST_DIR})

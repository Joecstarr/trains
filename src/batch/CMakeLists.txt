add_library(batch_lib STATIC batch.cpp)

target_link_libraries(batch_lib trains_lib)


target_include_directories(batch_lib PUBLIC ${CMAKE_CURRENT_LIST_DIR})

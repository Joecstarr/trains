add_executable(trains_program frontend.cpp)

target_link_libraries(trains_program batch_lib trains_lib)

target_include_directories(trains_program PUBLIC ${CMAKE_CURRENT_LIST_DIR})
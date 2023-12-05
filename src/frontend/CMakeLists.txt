add_executable(frontend frontend.cpp)

target_link_libraries(frontend batch_lib trains_lib)

target_include_directories(frontend PUBLIC ${CMAKE_CURRENT_LIST_DIR})
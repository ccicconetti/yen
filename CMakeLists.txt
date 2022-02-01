add_library(yen SHARED
  ${CMAKE_CURRENT_SOURCE_DIR}/custom_dijkstra_call.hpp
  ${CMAKE_CURRENT_SOURCE_DIR}/yen_ksp.cc
)

target_link_libraries(yen
)

add_executable(index index.cpp)
target_link_libraries(index
  PUBLIC
  nlohmann_json::nlohmann_json
  spdlog::spdlog
  )

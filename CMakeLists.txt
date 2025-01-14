add_library(uint256_t uint256_t.h uint256_t.cpp)
target_link_libraries(uint256_t PRIVATE uint128_t)
target_include_directories(uint256_t PUBLIC .)

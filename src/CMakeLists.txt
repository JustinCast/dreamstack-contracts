project(teloscontracts)

set(EOSIO_WASM_OLD_BEHAVIOR "Off")
find_package(eosio.cdt)

add_contract( teloscontracts teloscontracts teloscontracts.cpp )
target_include_directories( teloscontracts PUBLIC ${CMAKE_SOURCE_DIR}/../include )
target_ricardian_directory( teloscontracts ${CMAKE_SOURCE_DIR}/../ricardian )
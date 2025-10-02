add_executable(cloud_durable_example
  cloud_durable_example.cc)
target_link_libraries(cloud_durable_example
  ${ROCKSDB_LIB})

add_executable(clone_example
  clone_example.cc)
target_link_libraries(clone_example
  ${ROCKSDB_LIB})

add_executable(cloud_dump
  cloud_dump.cc)
target_link_libraries(cloud_dump
  ${ROCKSDB_LIB})


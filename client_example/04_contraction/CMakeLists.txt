add_executable(client_contraction_scale_fp32 contraction_scale_fp32.cpp)
target_link_libraries(client_contraction_scale_fp32 PRIVATE composable_kernel::device_operations)
target_compile_features(client_contraction_scale PRIVATE cxx_std_17)

add_executable(client_contraction_bilinear_fp32 contraction_bilinear_fp32.cpp)
target_link_libraries(client_contraction_bilinear_fp32 PRIVATE composable_kernel::device_operations)
target_compile_features(client_contraction_bilinear PRIVATE cxx_std_17)

add_executable(client_contraction_scale_fp64 contraction_scale_fp64.cpp)
target_link_libraries(client_contraction_scale_fp64 PRIVATE composable_kernel::device_operations)
target_compile_features(client_contraction_scale_fp64 PRIVATE cxx_std_17)

add_executable(client_contraction_bilinear_fp64 contraction_bilinear_fp64.cpp)
target_link_libraries(client_contraction_bilinear_fp64 PRIVATE composable_kernel::device_operations)
target_compile_features(client_contraction_blinear_fp64 PRIVATE cxx_std_17)

add_executable(contraction_g1m2n3k1_add_xdl_fp16 contraction_g1m2n3k1_add_xdl_fp16.cpp)
target_link_libraries(contraction_g1m2n3k1_add_xdl_fp16 PRIVATE composable_kernel::device_operations)
target_compile_features(contraction_g1m2n3k1_add_xdl-fp16 PRIVATE cxx_std_17)

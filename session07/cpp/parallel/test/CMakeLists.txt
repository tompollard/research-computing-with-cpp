add_executable(catch catch.cpp)
add_executable(catch_mpi catch_mpi.cpp)
target_link_libraries(catch smooth_library  ${MPI_C_LIBRARIES} ${MPI_CXX_LIBRARIES})
target_link_libraries(catch_mpi smooth_library  ${MPI_C_LIBRARIES} ${MPI_CXX_LIBRARIES})

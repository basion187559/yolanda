add_executable(nonblockingserver nonblockingserver.c)
target_link_libraries(nonblockingserver yolanda)


add_executable(nonblockingclient nonblockingclient.c)
target_link_libraries(nonblockingclient yolanda)

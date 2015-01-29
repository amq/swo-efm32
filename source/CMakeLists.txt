# Copyright (C) 2013-2105 ARM Limited. All rights reserved.  

add_library(swo-platform
    swo-platform.c
)

target_link_libraries(swo-platform
    cmsis-core
)



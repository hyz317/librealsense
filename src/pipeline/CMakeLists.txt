target_sources(${LRS_TARGET}
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/pipeline.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/config.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/profile.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/aggregator.cpp"
        
        "${CMAKE_CURRENT_LIST_DIR}/pipeline.h"
        "${CMAKE_CURRENT_LIST_DIR}/config.h"
        "${CMAKE_CURRENT_LIST_DIR}/profile.h"
        "${CMAKE_CURRENT_LIST_DIR}/resolver.h"
        "${CMAKE_CURRENT_LIST_DIR}/aggregator.h"
)

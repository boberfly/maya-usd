target_sources(${PROJECT_NAME} 
    PRIVATE
        hdMtlx.cpp
)

set(HEADERS
    hdMtlx.h
)

# -----------------------------------------------------------------------------
# promoted headers
# -----------------------------------------------------------------------------
mayaUsd_promoteHeaderList(HEADERS ${HEADERS} SUBDIR hdMtlx)

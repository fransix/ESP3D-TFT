# Component directive
set(SOURCES "disp_spi.c")
set(INCLUDES .)
idf_component_register(SRCS ${SOURCES}
    INCLUDE_DIRS ${INCLUDES}
    REQUIRES lvgl
)

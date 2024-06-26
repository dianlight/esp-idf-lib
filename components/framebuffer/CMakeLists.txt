idf_component_register(
    SRCS framebuffer.c 
         fbanimation.c
    INCLUDE_DIRS .
    REQUIRES log color esp_timer
)


idf_component_register(SRCS "src/BNO055ESP32.cpp"
                    INCLUDE_DIRS "src/"
                    REQUIRES driver)

target_compile_options(${COMPONENT_LIB} PUBLIC -std=gnu++11)
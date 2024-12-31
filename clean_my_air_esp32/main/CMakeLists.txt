idf_component_register(SRCS "clean_my_air_esp32.c"
                    INCLUDE_DIRS "."
                    REQUIRES esp_wifi
                    REQUIRES nvs_flash)
                                        
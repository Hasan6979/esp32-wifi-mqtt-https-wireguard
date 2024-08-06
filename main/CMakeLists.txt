idf_component_register(SRCS "hello_world_main.c"
                    PRIV_REQUIRES spi_flash
                    INCLUDE_DIRS ""
                    REQUIRES mqtt
                    REQUIRES esp_http_client
                    REQUIRES esp_wifi esp_netif nvs_flash)

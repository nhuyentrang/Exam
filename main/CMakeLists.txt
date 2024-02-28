idf_component_register(SRCS "station_example_main.c"
                       REQUIRES esp_netif esp_event esp_http_server esp_http_client esp_https_ota esp_wifi esp_partition mqtt bt 
                       freertos spiffs nvs_flash driver vfs
                    INCLUDE_DIRS ".")

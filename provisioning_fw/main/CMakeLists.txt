# Main component CMakeLists.txt
idf_component_register(
        SRC_DIRS "."
        INCLUDE_DIRS "."
        REQUIRES bootloader_support console json esp_netif nvs_flash spiffs spi_flash mbedtls     
    )

idf_component_register(
	SRCS "projectMain.c" "oled.c" "u8g2_esp32_hal.c" "smartconfig_main.c"
	"wifi_eraseconfig.c"
    INCLUDE_DIRS "."
    REQUIRES u8g2 nvs_flash esp_http_server mqtt spiffs json)
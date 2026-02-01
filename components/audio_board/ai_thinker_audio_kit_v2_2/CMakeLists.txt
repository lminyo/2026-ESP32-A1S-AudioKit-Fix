idf_component_register(SRCS "board.c" "board_pins_config.c"
                       INCLUDE_DIRS "."
                       REQUIRES audio_board audio_hal esp_peripherals driver esp_common)

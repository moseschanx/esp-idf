idf_component_register(SRCS "usb_bt_tranceiver_main.c"
	    PRIV_REQUIRES bt nvs_flash esp_driver_uart console
                    INCLUDE_DIRS "."
                    )

zephyr_sources_ifdef(CONFIG_LP3943 lp3943.c)
zephyr_sources_ifdef(CONFIG_LP5562 lp5562.c)
zephyr_sources_ifdef(CONFIG_PCA9633 pca9633.c)

zephyr_sources_ifdef(CONFIG_USERSPACE   led_handlers.c)

# SPDX-License-Identifier: GPL-2.0

obj-$(CONFIG_ESP8089) += esp8089.o

ccflags-y += -DP2P_CONCURRENT -DESP_ACK_INTERRUPT -DESP_USE_SDIO
esp8089-y := esp_init.o
esp8089-y += esp_debug.o
esp8089-y += sdio_sif_esp.o
esp8089-y += esp_io.o
esp8089-y += esp_file.o
esp8089-y += esp_main.o
esp8089-y += esp_sip.o
esp8089-y += esp_ext.o
esp8089-y += esp_ctrl.o
esp8089-y += esp_mac80211.o
esp8089-y += esp_utils.o
esp8089-y += esp_pm.o

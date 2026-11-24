# SPDX-License-Identifier: GPL-2.0
# copyright (c) 2011 - 2012 espressif system
DRIVER_NAME := wlan

EXTRA_CFLAGS += -DDEBUG -DSIP_DEBUG -DFAST_TX_STATUS -DKERNEL_IV_WAR -DRX_SENDUP_SYNC -DDEBUG_FS -DSIF_DSR_WAR -DHAS_INIT_DATA -DHAS_FW -DESP_USE_SDIO -DESP_PREALLOC 

$(DRIVER_NAME)-y += esp_ctrl.o
$(DRIVER_NAME)-y += esp_debug.o
$(DRIVER_NAME)-y += esp_ext.o
$(DRIVER_NAME)-y += esp_file.o
$(DRIVER_NAME)-y += esp_io.o
$(DRIVER_NAME)-y += esp_mac80211.o
$(DRIVER_NAME)-y += esp_main.o
$(DRIVER_NAME)-y += esp_pm.o
$(DRIVER_NAME)-y += esp_sip.o
$(DRIVER_NAME)-y += esp_utils.o
$(DRIVER_NAME)-y += sdio_sif_esp.o
$(DRIVER_NAME)-y += testmode.o


obj-$(CONFIG_ESP8089) := $(DRIVER_NAME).o



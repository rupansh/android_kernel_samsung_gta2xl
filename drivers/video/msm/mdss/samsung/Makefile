#
# Samsung Common file.
#

obj-y += ss_self_display_common.o
obj-y += ss_dsi_panel_sysfs.o
obj-y += ss_dsi_panel_debug.o
obj-y += ss_dsi_panel_common.o
obj-y += ss_dsi_mdnie_lite_common.o
obj-y += ss_dsi_smart_dimming_common.o
obj-y += ss_regulator_common.o
obj-$(CONFIG_SAMSUNG_DEBUG_DISPLAY) += dlog.o
obj-$(CONFIG_DISPLAY_USE_INFO) += ss_dpui_common.o

# TO SUPPORT POC FLASH
obj-$(CONFIG_SUPPORT_POC_FLASH) += ss_ddi_poc_common.o

# TO SUPPORT SPI INTERFACE
# obj-y  += ss_ddi_spi_common.o

#
# panel directory make file
#

# TO SUPPORT PBA BOOINT
obj-y += PBA_BOOTING/

# GTAX
obj-$(CONFIG_PANEL_HX8279_TV101WUM_WUXGA) += HX8279_TV101WUM/

# C9 panel
obj-$(CONFIG_PANEL_S6E3FA3_AMS598NJ01_FHD) += S6E3FA3_AMS598NJ01/

#Jackpot
obj-$(CONFIG_PANEL_S6E3FA3_AMS559NK01_FHD) += S6E3FA3_AMS559NK01/
obj-$(CONFIG_PANEL_S6E3FA7_AMS559NK01_FHD) += S6E3FA7_AMS559NK01/

#Jackpot2
obj-$(CONFIG_PANEL_S6E3FA7_AMS604NL01_FHD) += S6E3FA7_AMS604NL01/

# J3-POP panel
obj-$(CONFIG_PANEL_TD4100_BV050HDM_HD) += TD4100_BV050HDM/

# J2 2018 OCTA 5.0" OCTA panel
obj-$(CONFIG_PANEL_EA8061S_AMS498QV01_QHD) += EA8061S_AMS498QV01/

# J6p
obj-$(CONFIG_PANEL_S6E8AA5X01_AMS561RA01_HD) += S6E8AA5X01_AMS561RA01/

#GTES 2018
obj-$(CONFIG_PANEL_S6D7AA0X11_TV080WXM_WXGA) += S6D7AA0X11_TV080WXM/

# J7-POP panel
obj-$(CONFIG_PANEL_TD4100_5_5_HD) += TD4100_5_5/

#
# BLIC
#
obj-$(CONFIG_BLIC_ISL98611)	+= isl98611/
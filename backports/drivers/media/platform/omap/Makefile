#
# Makefile for the omap video device drivers.
#

# OMAP2/3 Display driver
omap-vout-y += omap_vout.o omap_voutlib.o
omap-vout-$(CONFIG_BACKPORT_VIDEO_OMAP2_VOUT_VRFB) += omap_vout_vrfb.o
obj-$(CONFIG_BACKPORT_VIDEO_OMAP2_VOUT) += omap-vout.o

# 
# Copyright (C) 2006-2009 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=mini2440
BOARDNAME:=MINI2440 Dev Board
FEATURES:=jffs2 usb tgz jffs2
LINUX_VERSION:=2.6.32.2
#DEVICE_TYPE=phone

include $(INCLUDE_DIR)/target.mk
# DEFAULT_PACKAGES += wpad-mini kmod-switch gpioctl

KERNELNAME:="uImage"

define Target/Description
  Build fimware images for Chinese Samsung 2440 touch screen board.
endef

$(eval $(call BuildTarget))

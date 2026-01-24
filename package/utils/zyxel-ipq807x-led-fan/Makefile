#
# Copyright (c) 2026 Agustin Lorenzo <agustin.lorenzo@thinco.es>
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=zyxel-ipq807x-led-fan
PKG_RELEASE:=1
PKG_FLAGS:=nonshared

include $(INCLUDE_DIR)/package.mk

define Package/zyxel-ipq807x-led-fan
    SECTION:=utils
    CATEGORY:=Base system
    TITLE:=Utilities for managing LED and fan settings on ZyXEL NBG7815
    MAINTAINER:=Agustin Lorenzo <agustin.lorenzo@thinco.es>
    DEPENDS:=@TARGET_qualcommax_ipq807x
endef

define Package/zyxel-ipq807x-led-fan/description
   This package contains utilities for managing the configuration of LEDs and fans on ZyXEL NBG7815 device.
endef

define Build/Prepare
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/zyxel-ipq807x-led-fan/install
	$(CP) ./files/* $(1)/
endef

$(eval $(call BuildPackage,zyxel-ipq807x-led-fan))

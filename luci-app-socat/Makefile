# Copyright (C) 2020 Lienol <lawlienol@gmail.com>
#
# This is free software, licensed under the GNU General Public License v3.
#

include $(TOPDIR)/rules.mk

PKG_VERSION:=20220823-1
PKG_RELEASE:=2
LUCI_TITLE:=LuCI support for Socat
LUCI_DEPENDS:=+socat
LUCI_PKGARCH:=all

define Package/luci-app-socat/conffiles
/etc/config/socat_luci
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature

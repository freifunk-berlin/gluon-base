# Copyright (C) 2013 Nils Schneider <nils at nilsschneider.net>
# This is free software, licensed under the Apache 2.0 license.

include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-web-network
PKG_VERSION:=1
PKG_RELEASE:=1

include ../gluon.mk

define Package/gluon-web-network
  TITLE:=gluon-web module for network port configuration
  DEPENDS:=+gluon-web-admin +gluon-client-bridge
endef

$(eval $(call BuildPackageGluon,gluon-web-network))

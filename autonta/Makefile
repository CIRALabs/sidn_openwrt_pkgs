#
# Copyright (C) 2016 SIDN
#

include $(TOPDIR)/rules.mk

PKG_NAME:=autonta
PKG_VERSION:=0.0.1
PKG_RELEASE:=1

PKG_LICENSE:=BSD-3-Clause
PKG_LICENSE_FILES:=LICENSE
PKG_MAINTAINER:=Jelte Jansen <jelte.jansen@sidn.nl>

PKG_BUILD_DIR:=$(BUILD_DIR)/autonta-$(PKG_VERSION)
PKG_SOURCE:=autonta-$(PKG_VERSION).tar.gz
PKG_SOURCE_URL:=http://tjeb.nl/opendir/autonta
PKG_SHA256SUM:=d95ec2d6acee7da03443ce64961e168f0109fd252bb5b7f1fbc4f8d7d7c539de

include $(INCLUDE_DIR)/package.mk

define Package/autonta/Default
  TITLE:=Negative Trust Anchor management
  URL:=http://valibox.sidnlabs.nl
endef

define Package/autonta
  $(call Package/autonta/Default)
  SECTION:=base
  CATEGORY:=Network
  SUBMENU:=SIDN
  TITLE+= (daemon)
#  DEPENDS+= 
endef

define Package/sidn-unbound/description
  This package contains the web-interface for negative trust anchors
endef

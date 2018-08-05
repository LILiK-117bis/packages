include $(TOPDIR)/rules.mk

PKG_NAME:=lilik
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/lilik
  SECTION:=meta
  CATEGORY:=LILiK
  DEPENDS:=+ca-bundle +ca-certificates +dnsmasq-full +reverse-proxy +ansible +openssl-util
  TITLE:=LILiK meta-package
endef

define Package/lilik/description
  LILiK Meta-package all our OpenWRT needs
endef


$(eval $(call BuildPackage,lilik))

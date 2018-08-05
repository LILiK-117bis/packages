include $(TOPDIR)/rules.mk

PKG_NAME:=reverseproxy
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/reverseproxy
  SECTION:=meta
  CATEGORY:=LILiK
  DEPENDS:=+nginx-all-module
  TITLE:=reverse proxy meta package
endef

define Package/reverseproxy/description
  LILiK's reverse proxy meta-package
endef

Package/reverseproxy/conffiles = $(Package/nginx/conffiles)

define Build/Configure
endef

define Build/Compile
endef

define Package/reverseproxy/install
  $(INSTALL_DIR) $(1)/etc/nginx/http.conf.d
  $(INSTALL_DIR) $(1)/etc/nginx/map.conf.d
  $(INSTALL_DIR) $(1)/etc/nginx/upstream.conf.d
endef

$(eval $(call BuildPackage,reverseproxy))

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

Package/reverseproxy/conffiles = $(Package/nginx/conffiles)

define Package/reverseproxy/build
  true
endef

define Package/reverseproxy/install
  $(INSTALL_DIR) $(1)/etc/nginx/map.conf.d
endef

define Package/reverseproxy/description
  LILiK's reverse proxy meta-package
endef


# This command is always the last, it uses the definitions and variables we give above in order to get the job done
$(eval $(call BuildPackage,reverseproxy))

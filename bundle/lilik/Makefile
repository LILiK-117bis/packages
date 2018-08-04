include $(TOPDIR)/rules.mk

PKG_NAME:=lilik
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/lilik
  SECTION:=bundles
  CATEGORY:=Bundles
  DEPENDS:=+ca-bundle +ca-certificates +dnsmasq-full +nginx-all +openssh-server +openss-clients
  TITLE:=LILiK meta-package
endef

define Package/lilik/description
  LILiK Meta-package all our OpenWRT needs
endef


# This command is always the last, it uses the definitions and variables we give above in order to get the job done
$(eval $(call BuildPackage,lilik))

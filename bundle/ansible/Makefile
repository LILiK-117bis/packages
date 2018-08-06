# vim: set noexpandtab:

include $(TOPDIR)/rules.mk

PKG_NAME:=ansible
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/ansible
	SECTION:=meta
	CATEGORY:=LILiK
	DEPENDS:=+python +python3 +openssh-server +openssh-client +openssh-client-utils
	TITLE:=requirements to configure OpenWRT using ansible
endef

define Package/ansible/description
LILiK's meta-package for ansible requirements

endef

$(eval $(call BuildPackage,ansible))

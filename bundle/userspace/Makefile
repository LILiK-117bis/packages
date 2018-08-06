# vim: set noexpandtab:

include $(TOPDIR)/rules.mk

PKG_NAME:=userspace
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/userspace
	SECTION:=meta
	CATEGORY:=LILiK
	DEPENDS:=+bash +coreutils +gawk +grep +less-wide +screen +tar +tmux +tree
	TITLE:=userspace meta-package
endef

define Package/lilik/description
All your userspace tools are here.

endef


$(eval $(call BuildPackage,userspace))

# vim: set noexpandtab:

include $(TOPDIR)/rules.mk

PKG_NAME:=editors
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/editors
	SECTION:=meta
	CATEGORY:=LILiK
	DEPENDS:=+nano +vim-fuller +vim-help
	TITLE:=LILiK meta-package
endef

define Package/editors/description
LILiK's meta-package for all our editors
- nano
- vim

endef


$(eval $(call BuildPackage,editors))

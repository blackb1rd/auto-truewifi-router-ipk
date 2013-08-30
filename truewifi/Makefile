# 
# Script auto connect @TRUEWIFI
#

include $(TOPDIR)/rules.mk

PKG_NAME:=truewifi
PKG_VERSION:=1
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/truewifi
	CATEGORY:=Utilities
	TITLE:=Script auto connect @TRUEWIFI
	URL:=http://s4m3l0.exteen.com
	DEPENDS:=+libcurl +libopenssl
	PKGARCH:=all
	MAINTAINER:=s4m3l0 <blackb1rd@riseup.net>
endef

define Build/Compile
	true
endef

define Package/truewifi/install
	$(INSTALL_DIR) $(1)/usr/bin
	$(INSTALL_BIN) ./files/truecond $(1)/usr/bin/truecond
	$(INSTALL_DIR) $(1)/etc/init.d
	$(INSTALL_BIN) ./files/truenet $(1)/etc/init.d/truenet
	$(INSTALL_DIR) $(1)/etc/rc.d
	ln -sf /etc/init.d/truenet $(1)/etc/rc.d/S99truenet
endef

$(eval $(call BuildPackage,truewifi))

include $(TOPDIR)/rules.mk
include $(INCLUDE_DIR)/kernel.mk

PKG_NAME:=switch-rtl9303
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define KernelPackage/switch-rtl9303
  SECTION:=kernel
  CATEGORY:=Kernel modules
  SUBMENU:=Network Devices
  TITLE:=Realtek RTL9303 switch support
  DEPENDS:=+kmod-i2c-gpio
  FILES:= $(PKG_BUILD_DIR)/rtl9303.ko
  AUTOLOAD:=$(call AutoProbe,rtl9303)
endef

include $(INCLUDE_DIR)/kernel-defaults.mk

define Build/Compile
endef

$(eval $(call KernelPackage,switch-rtl9303))

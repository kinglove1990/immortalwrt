#
# Copyright (C) 2013-2016 OpenWrt.org
# Copyright (C) 2017 Yousong Zhou
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk
include $(INCLUDE_DIR)/kernel.mk

PKG_VERSION:=2025.01
PKG_HASH:=cdef7d507c93f1bbd9f015ea9bc21fa074268481405501945abc6f854d5b686f

PKG_MAINTAINER:=Zoltan HERPAI <wigyori@uid0.hu>

UBOOT_USE_INTREE_DTC:=1

include $(INCLUDE_DIR)/u-boot.mk
include $(INCLUDE_DIR)/package.mk

define U-Boot/Default
  BUILD_TARGET:=sunxi
  UBOOT_IMAGE:=u-boot-sunxi-with-spl.bin
  UENV:=default
  HIDDEN:=1
endef

define U-Boot/a64-olinuxino
  BUILD_SUBTARGET:=cortexa53
  NAME:=Olimex A64-OLinuXino
  BUILD_DEVICES:=olimex_a64-olinuxino
  DEPENDS:=+PACKAGE_u-boot-olimex_a64-olinuxino:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/a64-olinuxino-emmc
  BUILD_SUBTARGET:=cortexa53
  NAME:=Olimex A64-OLinuXino eMMC
  BUILD_DEVICES:=olimex_a64-olinuxino-emmc
  DEPENDS:=+PACKAGE_u-boot-olimex_a64-olinuxino-emmc:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/A10-OLinuXino-Lime
  BUILD_SUBTARGET:=cortexa8
  NAME:=A10 OLinuXino LIME
  BUILD_DEVICES:=olimex_a10-olinuxino-lime
endef

define U-Boot/A13-OLinuXino
  BUILD_SUBTARGET:=cortexa8
  NAME:=A13 OlinuXino
  BUILD_DEVICES:=olimex_a13-olinuxino
endef

define U-Boot/A20-OLinuXino-Lime
  BUILD_SUBTARGET:=cortexa7
  NAME:=A20 OLinuXino LIME
  BUILD_DEVICES:=olimex_a20-olinuxino-lime
endef

define U-Boot/A20-OLinuXino-Lime2
  BUILD_SUBTARGET:=cortexa7
  NAME:=A20 OLinuXino LIME2
  BUILD_DEVICES:=olimex_a20-olinuxino-lime2
endef

define U-Boot/A20-OLinuXino-Lime2-eMMC
  BUILD_SUBTARGET:=cortexa7
  NAME:=A20 OLinuXino LIME2 eMMC
  BUILD_DEVICES:=olimex_a20-olinuxino-lime2-emmc
endef

define U-Boot/A20-OLinuXino_MICRO
  BUILD_SUBTARGET:=cortexa7
  NAME:=A20 OLinuXino MICRO
  BUILD_DEVICES:=olimex_a20-olinuxino-micro
endef

define U-Boot/Bananapi
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapi
  BUILD_DEVICES:=lemaker_bananapi
endef

define U-Boot/Bananapro
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapro
  BUILD_DEVICES:=lemaker_bananapro
endef

define U-Boot/beelink_x2
  BUILD_SUBTARGET:=cortexa7
  NAME:=Beelink X2 (H3)
  BUILD_DEVICES:=roofull_beelink-x2
endef

define U-Boot/Cubieboard
  BUILD_SUBTARGET:=cortexa8
  NAME:=Cubieboard
  BUILD_DEVICES:=cubietech_a10-cubieboard
endef

define U-Boot/Cubieboard2
  BUILD_SUBTARGET:=cortexa7
  NAME:=Cubieboard2
  BUILD_DEVICES:=cubietech_cubieboard2
endef

define U-Boot/Cubietruck
  BUILD_SUBTARGET:=cortexa7
  NAME:=Cubietruck
  BUILD_DEVICES:=cubietech_cubietruck
endef

define U-Boot/Hummingbird_A31
  BUILD_SUBTARGET:=cortexa7
  NAME:=Hummingbird A31 board
  BUILD_DEVICES:=merrii_hummingbird
endef

define U-Boot/Marsboard_A10
  BUILD_SUBTARGET:=cortexa8
  NAME:=HAOYU Marsboard A10
  BUILD_DEVICES:=haoyu_a10-marsboard
endef

define U-Boot/Mele_M9
  BUILD_SUBTARGET:=cortexa7
  NAME:=Mele M9 (A31)
  BUILD_DEVICES:=mele_m9
endef

define U-Boot/OLIMEX_A13_SOM
  BUILD_SUBTARGET:=cortexa8
  NAME:=Olimex A13 SOM
  BUILD_DEVICES:=olimex_a13-olimex-som
endef

define U-Boot/Linksprite_pcDuino
  BUILD_SUBTARGET:=cortexa8
  NAME:=Linksprite pcDuino
  BUILD_DEVICES:=linksprite_a10-pcduino
endef

define U-Boot/LicheePi_Zero
  BUILD_SUBTARGET:=cortexa7
  NAME:=Lichee Pi Zero V3s
  BUILD_DEVICES:=licheepi_licheepi-zero-dock
endef

define U-Boot/Linksprite_pcDuino3
  BUILD_SUBTARGET:=cortexa7
  NAME:=Linksprite pcDuino3
  BUILD_DEVICES:=linksprite_pcduino3
endef

define U-Boot/Linksprite_pcDuino3_Nano
  BUILD_SUBTARGET:=cortexa7
  NAME:=Linksprite pcDuino3 Nano
  BUILD_DEVICES:=linksprite_pcduino3-nano
endef

define U-Boot/Lamobo_R1
  BUILD_SUBTARGET:=cortexa7
  NAME:=Lamobo R1
  BUILD_DEVICES:=lamobo_lamobo-r1
endef

define U-Boot/nanopi_m1_plus
  BUILD_SUBTARGET:=cortexa7
  NAME:=NanoPi M1 Plus (H3)
  BUILD_DEVICES:=friendlyarm_nanopi-m1-plus
endef

define U-Boot/zeropi
  BUILD_SUBTARGET:=cortexa7
  NAME:=ZeroPi (H3)
  BUILD_DEVICES:=friendlyarm_zeropi
endef

define U-Boot/nanopi_neo_air
  BUILD_SUBTARGET:=cortexa7
  NAME:=U-Boot for NanoPi NEO Air (H3)
  BUILD_DEVICES:=friendlyarm_nanopi-neo-air
endef

define U-Boot/nanopi_neo
  BUILD_SUBTARGET:=cortexa7
  NAME:=U-Boot for NanoPi NEO (H3)
  BUILD_DEVICES:=friendlyarm_nanopi-neo
endef

define U-Boot/nanopi_r1
  BUILD_SUBTARGET:=cortexa7
  NAME:=U-Boot for NanoPi R1 (H3)
  BUILD_DEVICES:=friendlyarm_nanopi-r1
endef

define U-Boot/orangepi_r1
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi R1 (H2+)
  BUILD_DEVICES:=xunlong_orangepi-r1
endef

define U-Boot/orangepi_zero
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi Zero (H2+)
  BUILD_DEVICES:=xunlong_orangepi-zero
endef

define U-Boot/orangepi_one
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi One (H3)
  BUILD_DEVICES:=xunlong_orangepi-one
endef

define U-Boot/orangepi_one_plus
  BUILD_SUBTARGET:=cortexa53
  NAME:=Orange Pi One Plus (H6)
  DEPENDS:=+PACKAGE_u-boot-orangepi_one_plus:trusted-firmware-a-sunxi-h6
  BUILD_DEVICES:=xunlong_orangepi-one-plus
  UENV:=h6
  ATF:=h6
endef

define U-Boot/orangepi_pc
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi PC (H3)
  BUILD_DEVICES:=xunlong_orangepi-pc
endef

define U-Boot/orangepi_pc_plus
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi PC Plus (H3)
  BUILD_DEVICES:=xunlong_orangepi-pc-plus
endef

define U-Boot/orangepi_plus
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi Plus (H3)
  BUILD_DEVICES:=xunlong_orangepi-plus
endef

define U-Boot/orangepi_2
  BUILD_SUBTARGET:=cortexa7
  NAME:=Orange Pi 2 (H3)
  BUILD_DEVICES:=xunlong_orangepi-2
endef

define U-Boot/pangolin
  BUILD_SUBTARGET:=cortexa7
  NAME:=Theobroma A31-yQ7 devboard
  UENV:=pangolin
endef

define U-Boot/libretech_all_h3_cc_h5
  BUILD_SUBTARGET:=cortexa53
  NAME:=Libre Computer ALL-H3-CC H5
  BUILD_DEVICES:=libretech_all-h3-cc-h5
  DEPENDS:=+PACKAGE_u-boot-libretech_all_h3_cc_h5:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/nanopi_neo_plus2
  BUILD_SUBTARGET:=cortexa53
  NAME:=NanoPi NEO Plus2 (H5)
  BUILD_DEVICES:=friendlyarm_nanopi-neo-plus2
  DEPENDS:=+PACKAGE_u-boot-nanopi_neo_plus2:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/nanopi_neo2
  BUILD_SUBTARGET:=cortexa53
  NAME:=NanoPi NEO2 (H5)
  BUILD_DEVICES:=friendlyarm_nanopi-neo2
  DEPENDS:=+PACKAGE_u-boot-nanopi_neo2:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/nanopi_r1s_h5
  BUILD_SUBTARGET:=cortexa53
  NAME:=NanoPi R1S (H5)
  BUILD_DEVICES:=friendlyarm_nanopi-r1s-h5
  DEPENDS:=+PACKAGE_u-boot-nanopi_r1s_h5:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/pine64_plus
  BUILD_SUBTARGET:=cortexa53
  NAME:=Pine64 Plus A64
  BUILD_DEVICES:=pine64_pine64-plus
  DEPENDS:=+PACKAGE_u-boot-pine64_plus:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/bananapi_m2_plus_h3
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapi M2 Plus H3
  BUILD_DEVICES:=sinovoip_bananapi-m2-plus
endef

define U-Boot/Sinovoip_BPI_M3
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapi M3
  BUILD_DEVICES:=sinovoip_bananapi-m3
endef

define U-Boot/sopine_baseboard
  BUILD_SUBTARGET:=cortexa53
  NAME:=Sopine Baseboard
  BUILD_DEVICES:=pine64_sopine-baseboard
  DEPENDS:=+PACKAGE_u-boot-sopine_baseboard:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef


define U-Boot/orangepi_zero_plus
  BUILD_SUBTARGET:=cortexa53
  NAME:=Xunlong Orange Pi Zero Plus
  BUILD_DEVICES:=xunlong_orangepi-zero-plus
  DEPENDS:=+PACKAGE_u-boot-orangepi_zero_plus:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/orangepi_pc2
  BUILD_SUBTARGET:=cortexa53
  NAME:=Xunlong Orange Pi PC2
  BUILD_DEVICES:=xunlong_orangepi-pc2
  DEPENDS:=+PACKAGE_u-boot-orangepi_pc2:trusted-firmware-a-sunxi-a64
  UENV:=a64
  ATF:=a64
endef

define U-Boot/orangepi_zero2
  BUILD_SUBTARGET:=cortexa53
  NAME:=Xunlong Orange Pi Zero2
  BUILD_DEVICES:=xunlong_orangepi-zero2
  DEPENDS:=+PACKAGE_u-boot-orangepi_zero2:trusted-firmware-a-sunxi-h616
  UENV:=h616
  ATF:=h616
endef

define U-Boot/orangepi_zero2w
  BUILD_SUBTARGET:=cortexa53
  NAME:=Xunlong Orange Pi Zero2W
  BUILD_DEVICES:=xunlong_orangepi-zero2w
  DEPENDS:=+PACKAGE_u-boot-orangepi_zero2w:trusted-firmware-a-sunxi-h616
  UENV:=h616
  ATF:=h616
endef

define U-Boot/orangepi_zero3
  BUILD_SUBTARGET:=cortexa53
  NAME:=Xunlong Orange Pi Zero3
  BUILD_DEVICES:=xunlong_orangepi-zero3
  DEPENDS:=+PACKAGE_u-boot-orangepi_zero3:trusted-firmware-a-sunxi-h616
  UENV:=h616
  ATF:=h616
endef

define U-Boot/Bananapi_M2_Ultra
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapi M2 Ultra
  BUILD_DEVICES:=sinovoip_bananapi-m2-ultra
endef

define U-Boot/bananapi_m2_berry
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapi M2 Berry
  BUILD_DEVICES:=sinovoip_bananapi-m2-berry
endef

define U-Boot/bananapi_p2_zero
  BUILD_SUBTARGET:=cortexa7
  NAME:=Bananapi P2 Zero
  BUILD_DEVICES:=sinovoip_bananapi-p2-zero
endef


UBOOT_TARGETS := \
	a64-olinuxino \
	a64-olinuxino-emmc \
	A10-OLinuXino-Lime \
	A13-OLinuXino \
	A20-OLinuXino-Lime \
	A20-OLinuXino-Lime2 \
	A20-OLinuXino-Lime2-eMMC \
	A20-OLinuXino_MICRO \
	bananapi_m2_plus_h3 \
	Bananapi \
	bananapi_m2_berry \
	bananapi_p2_zero \
	Bananapi_M2_Ultra \
	Bananapro \
	beelink_x2 \
	Cubieboard \
	Cubieboard2 \
	Cubietruck \
	Hummingbird_A31 \
	Marsboard_A10 \
	Mele_M9 \
	OLIMEX_A13_SOM \
	LicheePi_Zero \
	Linksprite_pcDuino \
	Linksprite_pcDuino3 \
	Linksprite_pcDuino3_Nano \
	Lamobo_R1 \
	nanopi_m1_plus \
	zeropi \
	nanopi_neo \
	nanopi_neo_air \
	nanopi_neo_plus2 \
	nanopi_neo2 \
	nanopi_r1 \
	nanopi_r1s_h5 \
	orangepi_zero \
	orangepi_r1 \
	orangepi_one \
	orangepi_one_plus \
	orangepi_pc \
	orangepi_pc_plus \
	orangepi_plus \
	orangepi_2 \
	orangepi_pc2 \
	orangepi_zero2 \
	orangepi_zero2w \
	orangepi_zero3 \
	pangolin \
	pine64_plus \
	Sinovoip_BPI_M3 \
	sopine_baseboard \
	orangepi_zero_plus \
	libretech_all_h3_cc_h5

UBOOT_CONFIGURE_VARS += USE_PRIVATE_LIBGCC=yes

UBOOT_CUSTOMIZE_CONFIG := \
	--disable TOOLS_KWBIMAGE \
	--disable TOOLS_LIBCRYPTO \
	--disable TOOLS_MKEFICAPSULE

UBOOT_MAKE_FLAGS += \
	BL31=$(STAGING_DIR_IMAGE)/bl31_sunxi-$(ATF).bin SCP=/dev/null

define Build/InstallDev
	$(INSTALL_DIR) $(STAGING_DIR_IMAGE)
	$(CP) $(PKG_BUILD_DIR)/$(UBOOT_IMAGE) $(STAGING_DIR_IMAGE)/$(BUILD_DEVICES)-u-boot-with-spl.bin
	mkimage -C none -A arm -T script -d uEnv-$(UENV).txt \
		$(STAGING_DIR_IMAGE)/$(BUILD_DEVICES)-boot.scr
endef

define Package/u-boot/install/default
endef

$(eval $(call BuildPackage/U-Boot))

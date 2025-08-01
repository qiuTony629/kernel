# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	nanopi-m6-dsi0-amoled.dtbo \
	nanopi-m6-csi1-ov5647.dtbo \
	nanopi-m6-dsi0-800_1280-lcd.dts

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
	README.rockchip-overlays

targets += $(dtbo-y) $(dtbotxt-y)

always-y		:= $(dtbo-y) $(dtbotxt-y)
clean-files		:= *.dtbo


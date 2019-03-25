#dtbo-$(CONFIG_ARCH_SUNXI) += \
#	sun50i-a64-i2c0.dtbo \
#	sun50i-a64-i2c1.dtbo \
#	sun50i-a64-pps-gpio.dtbo \
#	sun50i-a64-spi-add-cs1.dtbo \
#	sun50i-a64-spi-jedec-nor.dtbo \
#	sun50i-a64-spi-spidev.dtbo \
#	sun50i-a64-uart1.dtbo \
#	sun50i-a64-uart2.dtbo \
#	sun50i-a64-uart3.dtbo \
#	sun50i-a64-uart4.dtbo \
#	sun50i-a64-w1-gpio.dtbo \
#  sun50i-a64-wiegandin.dtbo \
#  sun50i-a64-pcf8563.dtbo

scr-$(CONFIG_ARCH_SUNXI) += \
	sun50i-a64-fixup.scr

#dtbotxt-$(CONFIG_ARCH_SUNXI) += \
#	README.sun50i-a64-overlays

targets += $(dtbo-y) $(scr-y) $(dtbotxt-y)

always		:= $(dtbo-y) $(scr-y) $(dtbotxt-y)
clean-files	:= *.dtbo *.scr

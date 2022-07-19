ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_YUPIK) +=    \
	yupik-qrd-overlay.dtbo \
	yupik-qrd-pm7250b-overlay.dtbo


yupik-qrd-overlay.dtbo-base := yupik.dtb
yupik-qrd-pm7250b-overlay.dtbo-base := yupik.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo

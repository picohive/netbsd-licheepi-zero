### File list
* /usr/src/sys/arch/arm/sunxi/files.sunxi
* /usr/src/sys/arch/arm/sunxi/sun6i_dma.c
* /usr/src/sys/arch/arm/sunxi/sun8i_v3s_ccu.c
* /usr/src/sys/arch/arm/sunxi/sun8i_v3s_ccu.h
* /usr/src/sys/arch/arm/sunxi/sun8i_v3s_codec.c
* /usr/src/sys/arch/arm/sunxi/sun8i_v3s_gpio.c
* /usr/src/sys/arch/arm/sunxi/sunxi_codec.h
* /usr/src/sys/arch/arm/sunxi/sunxi_de2_ccu.c
* /usr/src/sys/arch/arm/sunxi/sunxi_drm.c
* /usr/src/sys/arch/arm/sunxi/sunxi_emac
* /usr/src/sys/arch/arm/sunxi/sunxi_gpio.c
* /usr/src/sys/arch/arm/sunxi/sunxi_gpio.h
* /usr/src/sys/arch/arm/sunxi/sunxi_lcdc.c
* /usr/src/sys/arch/arm/sunxi/sunxi_mixer.c
* /usr/src/sys/arch/arm/sunxi/sunxi_platform.c
* /usr/src/sys/arch/arm/sunxi/sunxi_pwm.c
* /usr/src/sys/arch/arm/sunxi/sunxi_usbphy.c
* /usr/src/sys/arch/evbarm/conf/LICHEEPI_ZERO

### Build the minimal kernel
./build.sh -U -u -O /usr/builds/obj.earmv7hf -T /usr/builds/tool.earmv7hf -j2 -m evbarm -a earmv7hf kernel=LICHEEPI_ZERO

### TODO
* Parallel RGB panel with sunxidrm support
* RTL8723BS WiFi/Bluetooth support

# lt220-uboot-v2016.11
mx7dlt220 u-boot v2016.11

# Download repository
	git clone https://github.com/OrgLT220/lt220-uboot-v2016.11.git
	cd lt220-uboot-v2016.11
	
# Install cross-compiler from yocto

# Setup cross-compile
	export ARCH=arm
	export CROSS_COMPILER=...

# Build
	make distclean
	make mx7dlt220_defconfig
	make
	cp u-boot.imx /var/lib/tftpboot/uboot-mx7dlt220.imx


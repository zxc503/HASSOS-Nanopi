## 编译
1. 删除buildroot/boot/uboot/uboot.mk下的 UBOOT_DEPENDENCIES += rockchip-blobs

2. sudo make nanopi_neo3 FORCE_UNSAFE_CONFIGURE=1 ARCH=aarch64

## 测试情况
+ Nanopi Neo 3：可以运行

obj-m += nailgun.o


KERNELDIR := ~/modulespath/lib/modules/4.14.114-v7+/build

CROSS_COMPILE=/home/czh/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin/arm-linux-gnueabihf-


all:
	make ARCH=arm -C $(KERNELDIR) M=$(PWD) CROSS_COMPILE=~/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin/arm-linux-gnueabihf- modules

clean:
	make -C $(KERNELDIR) M=$(PWD) clean

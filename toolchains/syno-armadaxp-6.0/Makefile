TC_NAME = syno-$(TC_ARCH)

TC_ARCH = armadaxp
TC_VERS = 6.0
TC_FIRMWARE = 6.0-7321

TC_DIST_NAME = armadaxp-gcc493_glibc220_hard-GPL.txz

TC_EXT = txz
TC_DIST_SITE = https://sourceforge.net/projects/dsgpl/files/DSM%206.0%20Tool%20Chains/Marvell%20Armada%20XP%20Linux%203.2.40

TC_BASE_DIR = arm-unknown-linux-gnueabi
TC_PREFIX = arm-unknown-linux-gnueabi
TC_TARGET = arm-unknown-linux-gnueabi

TC_CFLAGS = -I$(WORK_DIR)/$(TC_BASE_DIR)/$(TC_BASE_DIR)/libc/usr/include -mhard-float -mfpu=vfpv3-d16
TC_CPPFLAGS = -I$(WORK_DIR)/$(TC_BASE_DIR)/$(TC_BASE_DIR)/libc/usr/include -mhard-float -mfpu=vfpv3-d16
TC_CXXFLAGS = -I$(WORK_DIR)/$(TC_BASE_DIR)/$(TC_BASE_DIR)/libc/usr/include -mhard-float -mfpu=vfpv3-d16
TC_LDFLAGS = -L$(WORK_DIR)/$(TC_BASE_DIR)/$(TC_BASE_DIR)/libc/usr/lib -mhard-float -mfpu=vfpv3-d16

include ../../mk/spksrc.tc.mk

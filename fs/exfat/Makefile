# Exfat Linux kernel modules
# Public avaible at: https://github.com/rxrz/exfat-nofuse/
# Modified to compile with 3.4.x tree by Talustus <talustus@dream-irc.de>
# the code related to that makefile may not aply to GPL or other open licenses
#
# Rules for making the EXFAT driver.

obj-$(CONFIG_EXFAT_FS) += exfat.o

exfat-y	:= exfat_core.o exfat_api.o exfat_blkdev.o exfat_cache.o exfat_super.o \
		exfat_data.o exfat_global.o exfat_nls.o exfat_oal.o exfat_upcase.o

# Include
PWD		:= $(shell pwd)
ccflags-y 	:= -I$(PWD)

MODULE := znvpair

EXTRA_CFLAGS = $(ZFS_MODULE_CFLAGS)  -Wno-unused-but-set-variable -DHAVE_SPL -D_KERNEL -DTEXT_DOMAIN=\"zfs-linux-kernel\" -DNDEBUG 

obj-$(CONFIG_ZFS) := $(MODULE).o

$(MODULE)-objs += nvpair.o
$(MODULE)-objs += fnvpair.o
$(MODULE)-objs += nvpair_alloc_spl.o
$(MODULE)-objs += nvpair_alloc_fixed.o

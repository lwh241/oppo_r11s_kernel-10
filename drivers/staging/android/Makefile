ccflags-y += -I$(src)			# needed for trace events

obj-y					+= ion/

obj-$(CONFIG_ASHMEM)			+= ashmem.o
obj-$(CONFIG_ANDROID_TIMED_OUTPUT)	+= timed_output.o
obj-$(CONFIG_ANDROID_TIMED_GPIO)	+= timed_gpio.o
#ifdef CONFIG_PRODUCT_OPPO
#Jiemin.Zhu@PSW.AD.Performance.Memory.1139862, 2017/06/29, Add for monitor memleak
obj-$(CONFIG_ANDROID_LOW_MEMORY_KILLER)	+= oppo_lowmemorymonitor.o
#endif
obj-$(CONFIG_ANDROID_LOW_MEMORY_KILLER)	+= lowmemorykiller.o
obj-$(CONFIG_SYNC)			+= sync.o sync_debug.o
obj-$(CONFIG_SW_SYNC)			+= sw_sync.o
obj-$(CONFIG_ONESHOT_SYNC)		+= oneshot_sync.o
obj-$(CONFIG_ANDROID_VSOC)		+= vsoc.o

ifneq (, $(filter F%, $(SH_BUILD_ID)))
EXTRA_CFLAGS += -DSHGRIP_FACTORY_MODE_ENABLE
endif

ifeq ($(CONFIG_ARCH_LYNX_DL80),y)
obj-$(CONFIG_SENSOR_SHGRIP)	+= 003/
else ifeq ($(CONFIG_ARCH_PA30),y)
obj-$(CONFIG_SENSOR_SHGRIP) += 003/
else
obj-$(CONFIG_SENSOR_SHGRIP) += 002/
endif

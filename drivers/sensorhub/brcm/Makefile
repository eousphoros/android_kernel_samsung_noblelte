#
# Makefile for the sensor drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_SENSORS_SSP)		+= ssp_dev.o ssp_i2c.o ssp_data.o ssp_sysfs.o \
					ssp_input.o ssp_firmware.o ssp_debug.o
obj-$(CONFIG_SENSORS_SYSFS)		+= sensors_core.o

obj-$(CONFIG_IIO)			+= ssp_iio_ring.o ssp_iio_trigger.o

obj-$(CONFIG_SENSORS_SSP_ICM20610)	+= factory/
obj-$(CONFIG_SENSORS_SSP_MPU6500)	+= factory/
obj-$(CONFIG_SENSORS_SSP_BMI058)	+= factory/
obj-$(CONFIG_SENSORS_SSP_K6DS3TR)	+= factory/
obj-$(CONFIG_SENSORS_SSP_YAS532)	+= factory/
obj-$(CONFIG_SENSORS_SSP_YAS537)	+= factory/
obj-$(CONFIG_SENSORS_SSP_AK09911)	+= factory/

obj-$(CONFIG_SENSORS_SSP_TMG399x)	+= factory/
obj-$(CONFIG_SENSORS_SSP_TMD4903)	+= factory/
obj-$(CONFIG_SENSORS_SSP_BMP182)	+= factory/
obj-$(CONFIG_SENSORS_SSP_LPS25H)	+= factory/
obj-$(CONFIG_SENSORS_SSP_SHTC1)		+= factory/

obj-$(CONFIG_SENSORS_SSP_STM32F401)	+= factory/

obj-$(CONFIG_SENSORS_SSP_MOBEAM)	+= factory/
obj-$(CONFIG_SENSORS_SSP_SX9306)	+= factory/

obj-$(CONFIG_SENSORS_SSP_SENSORHUB)	+= ssp_sensorhub.o ssp_misc.o
obj-$(CONFIG_SENSORS_MAX86900)		+= max86900.o
obj-$(CONFIG_SENSORS_MAX86902)		+= max86902.o
obj-$(CONFIG_SENSORS_MAX_NOTCHFILTER)	+= max_notchfilter/
obj-$(CONFIG_SENSORS_ADPD142)		+= adpd142.o
obj-$(CONFIG_SENSORS_SX9310)		+= sx9310.o

obj-$(CONFIG_SENSORS_SSP_BBD)           += ssp_bbd.o factory/
obj-$(CONFIG_SENSORS_SSP_BBD)           += bbdpl/

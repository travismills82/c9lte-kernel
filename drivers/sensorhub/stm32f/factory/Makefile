#
# Makefile for the sensor drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_SENSORS_SSP_ACCEL)		+= accel_general.o
obj-$(CONFIG_SENSORS_SSP_6AXIS)	+= accel_general.o gyro_general.o
obj-$(CONFIG_SENSORS_SSP_TMD3700)       += light_tmd37xx.o prox_tmd37xx.o
obj-$(CONFIG_SENSORS_SSP_AK09916)	+= magnetic_common.o
obj-$(CONFIG_SENSORS_SSP_BMP280)	+= pressure_bmp280.o
obj-$(CONFIG_SENSORS_SSP_ATUC128L5HAR)	+= mcu_atuc128l5har.o
obj-$(CONFIG_SENSORS_SSP_MOBEAM)	+= barcode_emul_tmg3992.o

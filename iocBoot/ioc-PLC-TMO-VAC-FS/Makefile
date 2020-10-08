IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.2
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME := plc-tmo-vac
PROJECT_PATH := ../../plc-tmo-vac/plc-tmo-vac.tsproj
PLC := PLC_TMO_VAC_FS

PYTMC_OPTS := 
PREFIX := PREFIX

include $(IOC_TOP)/iocBoot/templates/Makefile.base

IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.4.1

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME = plc-mrco-motion
PROJECT_PATH := ../../lcls-plc-mrco-motion/lcls-plc-mrco-motion.tsproj
PLC = mrco_motion

PYTMC_OPTS :=
PREFIX = PLC:MRCO:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base


IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.4.1

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-xpp-jjslit-motion
PROJECT_PATH := ../../lcls-plc-xpp-jjslit-motion/lcls-plc-xpp-jjslit-motion.tsproj
PLC = xpp_jjslit_motion

PYTMC_OPTS :=
PREFIX = XPP

include $(IOC_TOP)/iocBoot/templates/Makefile.base


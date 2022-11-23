# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
#
# Makefile for the OPLUS Linux Kernel system team specific device drivers.
#

obj-y 	+= platform.o
obj-$(CONFIG_OPLUS_FEATURE_SHUTDOWN_DETECT)    += shutdown_detect/
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= oplus_project/
obj-$(CONFIG_OPLUS_FEATURE_QCOM_MINIDUMP_ENHANCE) 	+= qcom_minidump/
obj-$(CONFIG_OPLUS_FEATURE_SAUPWK)     += oplus_saupwk/
obj-$(CONFIG_OPLUS_FEATURE_DUMP_DEVICE_INFO)	+=  dump_device_info/
obj-$(CONFIG_OPLUS_FEATURE_CMDLINE)     += cmdline_parser/

ifdef CONFIG_OPLUS_SYSTEM_KERNEL_QCOM
obj-$(CONFIG_OPLUS_FEATURE_PROJECTINFO)	+=  project_info/
endif

#ifdef OPLUS_FEATURE_ESIM
obj-$(CONFIG_OPLUS_OPLUS_GPIO)    +=  oplus_gpio/
#endif /* OPLUS_FEATURE_ESIM */

#ifdef OPLUS_FEATURE_MISC
obj-y += misc/
#endif /* OPLUS_FEATURE_MISC */

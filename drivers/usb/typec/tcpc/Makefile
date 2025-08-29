subdir-ccflags-y += -Wall -Werror -DCONFIG_RT_REGMAP

obj-$(CONFIG_TCPC_RT1711H)	+= tcpc_rt1711h.o

tcpc_class-objs			+= tcpci_core.o tcpci_typec.o tcpci_timer.o \
	tcpm.o tcpci.o pd_dbg_info.o tcpci_alert.o rt-regmap.o tcpci_dual_role.o

obj-$(CONFIG_TCPC_CLASS)	+= tcpc_class.o rt_pd_manager.o

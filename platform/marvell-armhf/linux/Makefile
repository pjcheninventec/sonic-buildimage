.ONESHELL:
SHELL = /bin/bash
.SHELLFLAGS += -e

LINUX_KERNEL_MRVL_URL = https://github.com/antony-rheneus/sonic-marvell-binaries/raw/master/armhf/kernel/$(LINUX_KERNEL)

$(addprefix $(DEST)/, $(LINUX_KERNEL)): $(DEST)/% :
	# get deb package
	wget -O $(DEST)/$(LINUX_KERNEL) $(LINUX_KERNEL_MRVL_URL)


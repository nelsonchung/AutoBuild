
#===========INCLUDE================
include .config

#===========variable===============
DIR_ROOT = $(shell pwd)
DIR_BOARD = $(DIR_ROOT)/target

MAKE = PATH=$(DIR_ROOT)/bin:$(PATH); MAKE

export DIR_ROOT DIR_BOARD

TARGET = linux app romfs

all: $(TARGET)


#
# 0. linux
#
.PHONY: linux
linux:
	@echo "This is linux"
#
# 1. app 
#
.PHONY: app
app:
	@echo "This is app"
#
# 2. romfs 
#
.PHONY: romfs
romfs:
	@echo "This is romfs"

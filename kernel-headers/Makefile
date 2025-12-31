VERSION = 4
PATCHLEVEL = 9

headers_install:
	@mkdir -p $(O)/usr/include
	@rsync -mrq $(shell pwd)/* $(O)/usr/include

all:
	@true
#
#             LUFA Library
#     Copyright (C) Dean Camera, 2010.
#              
#  dean [at] fourwalledcubicle [dot] com
#      www.fourwalledcubicle.com
#

# Makefile to build all the LUFA Class Driver and Low Level Demos. Call with
# "make all" to rebuild all demos of both types.

# Projects are pre-cleaned before each one is built, to ensure any
# custom LUFA library build options are reflected in the compiled
# code.

%:
	$(MAKE) -C ClassDriver $@
	$(MAKE) -C LowLevel $@

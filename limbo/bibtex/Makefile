#==========================================================================
#                         Directories and names 
# ==========================================================================

LIMBO_ROOT_DIR = $(realpath ../..)

#==========================================================================
#                         Compilation Flags
# ==========================================================================

# include environmental configurations 
include $(LIMBO_ROOT_DIR)/Include.mk

# ==========================================================================
#                         Standard Setting
# ==========================================================================

.PHONY: install
install:
	mkdir -p $(PREFIX)/include/limbo/bibtex
	cp $(wildcard *.py) $(PREFIX)/include/limbo/bibtex

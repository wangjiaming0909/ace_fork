# -*- makefile -*-
#----------------------------------------------------------------------------
#       GNU ACE Workspace
#
# 
#
# This file was generated by MPC.  Any changes made directly to
# this file will be lost the next time it is generated.
#
# MPC Command:
# /home/johnny/DOC_ROOT/stage-6476/ACE_wrappers/bin/mwc.pl -type gnuace -exclude TAO/TAO_ACE.mwc -workers 8 -recurse -hierarchy -relative ACE_ROOT=/home/johnny/DOC_ROOT/stage-6476/ACE_wrappers -relative TAO_ROOT=/home/johnny/DOC_ROOT/stage-6476/ACE_wrappers/TAO
#
#----------------------------------------------------------------------------

MAKEFILE = GNUmakefile

ifeq ($(findstring k,$(MAKEFLAGS)),k)
  KEEP_GOING = -
endif

include $(ACE_ROOT)/include/makeinclude/macros.GNU

all: ACE ACE_Compression ACE_RLECompression ACE_ETCL ACE_ETCL_Parser ACE_FlReactor Monitor_Control-target SSL-target ACE_TkReactor ACE_XtReactor

depend: ACE-depend ACE_Compression-depend ACE_RLECompression-depend ACE_ETCL-depend ACE_ETCL_Parser-depend ACE_FlReactor-depend Monitor_Control-target-depend SSL-target-depend ACE_TkReactor-depend ACE_XtReactor-depend

REMAINING_TARGETS := $(filter-out all depend,$(TARGETS_NESTED:.nested=)) $(CUSTOM_TARGETS)
.PHONY: $(REMAINING_TARGETS)

$(REMAINING_TARGETS):
	$(KEEP_GOING)@$(MAKE) -f GNUmakefile.ACE $(@)
	$(KEEP_GOING)@cd Compression && $(MAKE) -f GNUmakefile.ACE_Compression $(@)
	$(KEEP_GOING)@cd Compression/rle && $(MAKE) -f GNUmakefile.ACE_RLECompression $(@)
	$(KEEP_GOING)@cd ETCL && $(MAKE) -f GNUmakefile.ACE_ETCL $(@)
	$(KEEP_GOING)@cd ETCL && $(MAKE) -f GNUmakefile.ACE_ETCL_Parser $(@)
	$(KEEP_GOING)@cd FlReactor && $(MAKE) -f GNUmakefile.ACE_FlReactor $(@)
	$(KEEP_GOING)@cd Monitor_Control && $(MAKE) -f GNUmakefile.Monitor_Control $(@)
	$(KEEP_GOING)@cd SSL && $(MAKE) -f GNUmakefile.SSL $(@)
	$(KEEP_GOING)@cd TkReactor && $(MAKE) -f GNUmakefile.ACE_TkReactor $(@)
	$(KEEP_GOING)@cd XtReactor && $(MAKE) -f GNUmakefile.ACE_XtReactor $(@)

.PHONY: ACE
ACE:
	$(KEEP_GOING)@$(MAKE) -f GNUmakefile.ACE all

.PHONY: ACE-depend
ACE-depend:
	$(KEEP_GOING)@$(MAKE) -f GNUmakefile.ACE depend

.PHONY: ACE_Compression
ACE_Compression: ACE
	$(KEEP_GOING)@cd Compression && $(MAKE) -f GNUmakefile.ACE_Compression all

.PHONY: ACE_Compression-depend
ACE_Compression-depend:
	$(KEEP_GOING)@cd Compression && $(MAKE) -f GNUmakefile.ACE_Compression depend

.PHONY: ACE_RLECompression
ACE_RLECompression: ACE ACE_Compression
	$(KEEP_GOING)@cd Compression/rle && $(MAKE) -f GNUmakefile.ACE_RLECompression all

.PHONY: ACE_RLECompression-depend
ACE_RLECompression-depend:
	$(KEEP_GOING)@cd Compression/rle && $(MAKE) -f GNUmakefile.ACE_RLECompression depend

.PHONY: ACE_ETCL
ACE_ETCL: ACE
	$(KEEP_GOING)@cd ETCL && $(MAKE) -f GNUmakefile.ACE_ETCL all

.PHONY: ACE_ETCL-depend
ACE_ETCL-depend:
	$(KEEP_GOING)@cd ETCL && $(MAKE) -f GNUmakefile.ACE_ETCL depend

.PHONY: ACE_ETCL_Parser
ACE_ETCL_Parser: ACE ACE_ETCL
	$(KEEP_GOING)@cd ETCL && $(MAKE) -f GNUmakefile.ACE_ETCL_Parser all

.PHONY: ACE_ETCL_Parser-depend
ACE_ETCL_Parser-depend:
	$(KEEP_GOING)@cd ETCL && $(MAKE) -f GNUmakefile.ACE_ETCL_Parser depend

.PHONY: ACE_FlReactor
ACE_FlReactor: ACE
	$(KEEP_GOING)@cd FlReactor && $(MAKE) -f GNUmakefile.ACE_FlReactor all

.PHONY: ACE_FlReactor-depend
ACE_FlReactor-depend:
	$(KEEP_GOING)@cd FlReactor && $(MAKE) -f GNUmakefile.ACE_FlReactor depend

.PHONY: Monitor_Control-target
Monitor_Control-target: ACE ACE_ETCL ACE_ETCL_Parser
	$(KEEP_GOING)@cd Monitor_Control && $(MAKE) -f GNUmakefile.Monitor_Control all

.PHONY: Monitor_Control-target-depend
Monitor_Control-target-depend:
	$(KEEP_GOING)@cd Monitor_Control && $(MAKE) -f GNUmakefile.Monitor_Control depend

.PHONY: SSL-target
SSL-target: ACE
	$(KEEP_GOING)@cd SSL && $(MAKE) -f GNUmakefile.SSL all

.PHONY: SSL-target-depend
SSL-target-depend:
	$(KEEP_GOING)@cd SSL && $(MAKE) -f GNUmakefile.SSL depend

.PHONY: ACE_TkReactor
ACE_TkReactor: ACE
	$(KEEP_GOING)@cd TkReactor && $(MAKE) -f GNUmakefile.ACE_TkReactor all

.PHONY: ACE_TkReactor-depend
ACE_TkReactor-depend:
	$(KEEP_GOING)@cd TkReactor && $(MAKE) -f GNUmakefile.ACE_TkReactor depend

.PHONY: ACE_XtReactor
ACE_XtReactor: ACE
	$(KEEP_GOING)@cd XtReactor && $(MAKE) -f GNUmakefile.ACE_XtReactor all

.PHONY: ACE_XtReactor-depend
ACE_XtReactor-depend:
	$(KEEP_GOING)@cd XtReactor && $(MAKE) -f GNUmakefile.ACE_XtReactor depend

project_name_list:
	@echo ACE_Compression
	@echo ACE_RLECompression
	@echo ACE_ETCL
	@echo ACE_ETCL_Parser
	@echo ACE_FlReactor
	@echo ACE
	@echo Monitor_Control-target
	@echo SSL-target
	@echo ACE_TkReactor
	@echo ACE_XtReactor
# -*-makefile-*-
# =========================================================================
#       item            : template Makefile dueca module
#       made by         : René van Paassen
#       date            : 010320
#       copyright       : (c) 2016 TUDelft-AE-C&S
# =========================================================================

# =========================================================================
#
# EDIT THIS SECTION ONLY TO ADJUST INCLUDE PATHS/DEFINES OR TO CHANGE
# THE DEFINITION OF WHAT YOUR SOURCE FILES ARE
#
# =========================================================================

# if needed, add the path to extra header files you need
EXTRA_INCLUDES = 

# Normally, in a comm-objects directory, there are no C++ source files
# other than those automatically generated from .dco files 
CPPSRC = 	

# And no C source files either
CSRC =		

# add all the files with the definitions of the generated-types (.dco files)
# this looks at the comm-objects.lst files in all 
DUECATYPES := 	$(shell if which dueca-listdco 2>/dev/null >/dev/null; then \
		  dueca-listdco; \
		  else ls *.dco 2>/dev/null; fi)

# version of this makefile
MAKEFILEVERSION = 1

################ including generic rules and targets #######################
TAILFILE =	$(shell dueca-config --path-datafiles)/data/MakefileTail.mod
include $(TAILFILE)
################ end generic rules and targets #############################

# ==========================================================================
#
# EDIT THIS SECTION ONLY IF YOU HAVE SPECIAL NEEDS (GENERATING INTERFACE
# CODE FROM GLADE ETC) THAT ARE NOT HANDLED BY THE NORMAL TARGETS/RULES
#
# ==========================================================================

# Put additional commands to be executed for "make all" here
local-all:

# Put additional commands to be executed for "make depend" here, for example
# interface files generated with glade?
local-depend:

# Put additional commands to be executed for "make clean" here
local-clean:

# Put additional commands to be executed for "make mrproper" here
local-mrproper:

# Put additional commands for locally generated code here
local-generated:
 


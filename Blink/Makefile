# Project Name
TARGET = Blink

# Configure for debugging
# common configurations:
# use DEBUG = 1 and OPT = -Og for debugging
# or DEBUG = 0 and OPT = -O3 for performance
DEBUG = 0
OPT = -O3

# Sources
CPP_SOURCES = main.cpp

LIBDAISY_DIR = ../libs/libDaisy
DAISYSP_DIR = ../libs/DaisySP

# (optional) Includes FatFS source files within project.
#USE_FATFS = 1

# Core location, and generic Makefile.
SYSTEM_FILES_DIR = $(LIBDAISY_DIR)/core
include $(SYSTEM_FILES_DIR)/Makefile

# Makefile for CH32V103R8
# 09-23-2023 E. Brombaugh

# sub directories
VPATH = .:../Peripheral/src:../Core:../Startup

# Object files
OBJECTS =   startup_ch32v10x.o core_riscv.o main.o debug.o \
			system_ch32v10x.o ch32v10x_it.o ch32v10x_misc.o \
			ch32v10x_pwr.o ch32v10x_rcc.o ch32v10x_gpio.o ch32v10x_usart.o
			
# Optional Linker script override
#LDSCRIPT = ../misc/CH32V103R8.ld

# Optional Optimization level override
#COPT = -O3

include ../misc/makefile.mk


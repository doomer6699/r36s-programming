# Makefile for R36S stuff
CFLAGS=-c -Wall -O2 
LIBS = -lm
PROG = devmem2
INCLUDES = -I. -I/usr/include

devmem2: devmem2.c
	gcc devmem2.c -o devmem2

clean:
	rm -rf *o $(PROG)

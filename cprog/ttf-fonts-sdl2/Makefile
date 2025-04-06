# Makefile for R36S stuff
CFLAGS=-c -Wall -O2 
LIBS = -lm
PROG = HelloSDL2
INCLUDES = -I. -I/usr/include

HelloSDL2: HelloSDL2.cpp
	g++ HelloSDL2.cpp -g -lSDL2 -lSDL2_ttf -lGLEW -lGL -o HelloSDL2

clean:
	rm -rf *o $(PROG)

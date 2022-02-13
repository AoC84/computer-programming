#
# Makefile that builds exc for exercise
# 
CC = gcc
CFLAGS = -pedantic -std=c89 -O -Wall 

all: exc

exc: example.c
	$(CC) $(CFLAGS) -o exc example.c

clean:
	rm -f *.o exc *~

GPLC   = gplc
CC     = gcc
CFLAGS = -g -Wall

# other local variables

#CFLAGS    = -O3
#CFLAGS = -O3 -fverbose-asm -fomit-frame-pointer
CFLAGS = -O3 -fverbose-asm -fomit-frame-pointer -fno-defer-pop

#CFLAGS= /Ox /Oy

opt:
	 $(CC) -S $(CFLAGS) asm_inst.c


no:
	 $(CC) -S asm_inst.c

clean:
	-rm *.s





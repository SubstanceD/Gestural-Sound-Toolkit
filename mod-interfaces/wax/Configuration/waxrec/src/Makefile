# Makefile

CC 		= gcc 
CFLAGS	= -isysroot /Developer/SDKs/MacOSX10.5.sdk \
	-mmacosx-version-min=10.5

all: build

build: Makefile waxrec.c
	$(CC) $(CFLAGS) -o waxrec waxrec.c

clean:
	rm -f waxrec.o core

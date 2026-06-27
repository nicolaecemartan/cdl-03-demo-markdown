CFLAGS =  -Wall -Wextra

.PHONY: all check test clean

all: helloworld

helloworld: helloworld.c

check:
	cpplint helloworld.c

test:
	./test.sh

clean:
	-rm -f helloworld
	-rm -f *~

CC=gcc
FLAGS=-Wall -Ofast -fomit-frame-pointer -msse -msse2 -msse3 -mmmx -m3dnow
INCLUDE=-I../../include
LINK=-L../../lib -lfft

all: nonlocal_vector

nonlocal_vector: nonlocal_vector.c
	$(CC)  $^ -o $@ $(FLAGS) $(INCLUDE) $(LINK)

clean:
	rm -f *.txt
	rm -f nonlocal_vector

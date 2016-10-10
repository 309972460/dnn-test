
CFLAGS= -O2 -std=c++11 -I ../ -ltbb
all: a.out

a.out: main.o
	clang++ $(CFLAGS) main.o

main.o: main.cpp
		clang++ $(CFLAGS) main.cpp -c

clean:
	rm -f *.o a.out

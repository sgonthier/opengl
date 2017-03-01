CFLAGS=-Wall -Wextra -g -std=c++11
LDFLAGS=

all: main

main: main.o UserInterface.o
	g++ $(LDFLAGS) $^ -o $@

%.o: %.cpp
	g++ $(CFLAGS) -c $< -o $@

clean: rm -f *.o

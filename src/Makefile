CFLAGS=-Wall -Wextra -g -std=c++11 
LDFLAGS=
OPTIONS=-lGL -lglut -lGLU

all: main

main: main.o UserInterface.o
	g++ $(LDFLAGS) $^ $(OPTIONS) -o $@

%.o: %.cpp
	g++ $(CFLAGS) -c $< $(OPTIONS) -o $@

clean: rm -f *.o
